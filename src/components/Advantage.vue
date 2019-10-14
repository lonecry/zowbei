<template>
    <div class="advantage">
        <div class="main">
            <img :src="require('@/assets/images/advantages.jpg')" alt="">
        </div>
    </div>
</template>

<script>
    export default {
        name: "Advantage"
    }
</script>


<style rel="stylesheet/scss" lang="scss" scoped>

    .advantage {
        display: block;
        .main {
            width: 1200px;
            height: 880px;
            display: block;
            margin: 0 auto;
            /*background: antiquewhite;*/
            overflow: hidden;
        }
    }

</style>