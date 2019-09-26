<template>
    <div class="hello">
        <Header></Header>
    </div>
</template>

<script>
    import Header from "./Header";

    export default {
        name: 'Index',
        data() {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        }
        ,
        components: {Header}
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    a {
        color: #42b983;
    }
</style>
