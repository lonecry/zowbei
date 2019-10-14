<template>
    <div class="hello">
        <Header></Header>
        <Swiperimg class="swiperindex"></Swiperimg>
        <Introduce class="intro"></Introduce>
        <Company></Company>
        <Advantage></Advantage>
    </div>
</template>

<script>
    import Header from "./Header";
    import Swiperimg from "./Swiperimg";
    import Introduce from './Introduce'
    import Company from './Company'
    import Advantage from './Advantage'

    export default {
        name: 'Index',
        data() {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        }
        ,
        components: {Header, Swiperimg, Introduce, Company, Advantage}
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    body {
        min-width: 1200px;
    }
    a {
        color: #42b983;
    }
    .swiperindex {
        width: 100%;
        overflow: hidden;
        display: block;
        /*height: auto;*/
    }
    .intro {
        /*margin-bottom: 100px;*/
    }
</style>
