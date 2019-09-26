<template>
    <div>
        <div class="headwarp">

            <div class="head"> {{msg}}</div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Index',
        data() {
            return {
                msg: 'This is Header'
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .headwarp {
        width: 100%;
        height: 118px;

    }

    .head {
        width: 1200px;
        height: 118px;
        display: block;
        margin: 0 auto;
        background: #42b983;
    }


</style>
