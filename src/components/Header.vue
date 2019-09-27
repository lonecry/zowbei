<template>
    <div>
        <div class="headwarp">
            <div class="head">
                <img src="../assets/images/logo.png" class="logo" alt="">
                <ul class="navul">
                    <li class="navli">首页</li>
                    <li class="navli">企业概况</li>
                    <li class="navli">产业布局</li>
                    <li class="navli">客户方案</li>
                    <li class="navli">新闻资讯</li>
                    <li class="navli">联系我们</li>
                </ul>
            </div>
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
        box-sizing: border-box;
        outline: 1px solid #42b983;
        background: #ffffff;
    }

    .logo {
        width: auto;
        height: 118px;
        display: block;
        float: left;
    }

    .navul {
        width: 1000px;
        float: left;
        height: 118px;
        /*outline: 1px solid #42b983;*/
        display: flex;
        flex-flow: row nowrap;
        justify-content: space-around;
        align-items: center;
    }

    .navli {
        float: left;
        width: 100px;
        height: 10px;
        line-height: 10px;
        padding: 10px;
        border-radius: 5px;
    }

    .navli:hover {
        background: #01a184;
        color: white;
        cursor: pointer;
    }


</style>
