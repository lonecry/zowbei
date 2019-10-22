<template>
    <div class="layout">
        <div class="layoutmain">
            <div>
                <span class="cstlayer"> </span>
                <div id="" type="title" class="entitle ">
                    <div class="wp-title_content">
                        <span class="titlespan"><strong>INDUSTRIAL DISTRIBUTION</strong></span>
                        <span class="titlespan" style="font-size: 30px">产业布局</span>
                    </div>
                </div>
            </div>
            <div class="content">
                <div class="item">
                    <img class="itemimg" :src="require('@/assets/images/c2.jpg')">
                    <span class="mask"></span>
                    <spn class="t1">环境影响评估</spn>
                    <spn class="t2">Environmental Impact Assessment</spn>
                </div>
                <div class="item"><img class="itemimg" :src="require('@/assets/images/c3.jpg')">
                    <span class="mask"></span>
                    <spn class="t1">环保验收</spn>
                    <spn class="t2">Environmental protection completion acceptance</spn>
                </div>
                <div class="item"><img class="itemimg" :src="require('@/assets/images/c4.jpg')">
                    <span class="mask"></span>
                    <spn class="t1">可行性研究报告编制</spn>
                    <spn class="t2">Feasibility study report preparation</spn>
                </div>
                <div class="item"><img class="itemimg" :src="require('@/assets/images/c5.jpg')">
                    <span class="mask"></span>
                    <spn class="t1">突发环境风险应急预案编制</spn>
                    <spn class="t2">Emergency environmental risk emergency plan</spn>
                </div>
                <div class="item"><img class="itemimg" :src="require('@/assets/images/c2.jpg')">
                    <span class="mask"></span>
                    <spn class="t1">环保管家服务</spn>
                    <spn class="t2">Environmental steward service</spn>
                </div>
                <div class="item"><img class="itemimg" :src="require('@/assets/images/c3.jpg')">
                    <span class="mask"></span>
                    <spn class="t1">环保设备销售</spn>
                    <spn class="t2">Environmental equipment sales</spn>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Company"
    }
</script>

<style rel="stylesheet/scss" lang="scss" scoped>


    .entitle {
        left: 77px;
        top: 126px;
        width: 614px;
        height: 53px;
        position: absolute;
        z-index: 106;
    }
    .cstlayer {
        left: 0px;
        top: 135px;
        width: 2px;
        height: 35px;
        position: absolute;
        z-index: 110;
        background: black;
    }
    .wp-title_content {
        border-width: 0px;
        border-color: transparent;
        padding: 0px;
        width: 614px;
        height: 53px;
        display: block;
        -ms-word-wrap: break-word;
    }
    .titlespan {
        display: block;
        color: rgb(34, 34, 34);
        text-transform: uppercase;
        font-family: 微软雅黑;
        font-size: 36px;
        text-align: left;
    }
    .layout {
        background: rgb(235, 235, 235);
    }
    .layoutmain {
        width: 1200px;
        height: 931px;
        display: block;
        margin: 0 auto;
        position: relative;
        overflow: hidden;
    }
    .layout {
        overflow: hidden;
        .content {
            width: 1170px;
            height: 504px;
            display: block;
            margin: 0 auto;
            margin-top: 359px;
            /*background: rgba(22, 235, 101, 0.21);*/
            display: flex;
            flex-flow: row wrap;
            justify-content: flex-start;
            align-items: center;
            .item {
                width: 390px;
                height: 252px;
                margin: 0;
                padding: 0;
                position: relative;
                z-index: 1;
                .itemimg {
                    width: 100%;
                    height: 100%;
                }
                .t1 {
                    position: absolute;
                    left: 25px;
                    bottom: 33px;
                    color: white;
                    font-size: 18px;
                }
                .t2 {
                    position: absolute;
                    left: 25px;
                    bottom: 11px;
                    color: white;
                    font-size: 14px;
                }
                .mask {
                    width: 100%;
                    height: 100%;
                    position: absolute;
                    left: 0;
                    top: 0;
                    background: rgba(0, 0, 0, 0.2);
                    display: none;
                }
            }
            .item:hover {
                z-index: 100;
                transition: 0.8s all ease;
                transition: 0.8s all ease;
                transform: translateY(-8%);
                box-shadow: 0 0 30px #ffffff;
                .mask {
                    display: block;
                }
            }
        }
    }

</style>


<!--
1、环境影响评估
2、环保竣工验收
3、可行性研究报告编制
4、突发环境风险应急预案编制
5、环保管家服务
6、环保设备销售
-->
