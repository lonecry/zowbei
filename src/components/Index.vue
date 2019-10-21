<template>
    <div class="hello">
        <Header></Header>
        <Swiperimg class="swiperindex"></Swiperimg>
        <Introduce class="intro"></Introduce>
        <Company></Company>
        <Advantage></Advantage>
        <Footer></Footer>
    </div>
</template>

<script>
    import Header from "./Header";
    import Swiperimg from "./Swiperimg";
    import Introduce from './Introduce'
    import Company from './Company'
    import Advantage from './Advantage'
    import Footer from "./Footer";

    export default {
        name      : 'Index',
        data() {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        },
        components: {Footer, Header, Swiperimg, Introduce, Company, Advantage, Footer}
    }
</script>

<style scoped>
    body {
        min-width : 1200px;
    }
    a {
        color : #42b983;
    }
    .swiperindex {
        width    : 100%;
        overflow : hidden;
        display  : block;
        /*height: auto;*/
    }
    .intro {
        /*margin-bottom: 100px;*/
    }
</style>
