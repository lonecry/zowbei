<template>
    <div class="root">
        <div class="maincenter">
            <div>
                <span class="cstlayer"> </span>
                <div id="" type="title" class="entitle ">
                    <div class="wp-title_content">
                        <span class="titlespan"><strong>Overview of Enterprises</strong></span>
                        <span class="titlespan" style="font-size: 30px">企业概况</span>
                    </div>
                </div>
            </div>
            <div class="js">
                <p>{{introduce1}}</p>
                <p>{{introduce2}}</p>
                <p>{{introduce3}}</p>
            </div>
            <img src="../assets/images/mou.png" class="introimg" alt="">
            <div class="oalist">
                <div class="introlist">
                    <img src="../assets/images/o1.png" class="itroicon" alt="">
                    <span class="intonum">100<span class="add">+</span></span>
                    <span class="span1">国家或地区</span>
                    <span class="span2">使用我们的产品</span>
                </div>
                <div class="introlist">
                    <img src="../assets/images/o2.png" class="itroicon" alt="">
                    <span class="intonum">125<span class="add">+</span></span>
                    <span class="span1">服务客户</span>
                    <span class="span2">获得我们的优质服务</span>
                </div>
                <div class="introlist">
                    <img src="../assets/images/o3.png" class="itroicon" alt="">
                    <span class="intonum">800<span class="add">+</span></span>
                    <span class="span1">专利注册项目</span>
                    <span class="span2">核心技术使我们始终领先</span>
                </div>
            </div>
        </div>
    </div>

</template>

<script>
    export default {
        name: "introduce",
        data() {
            return {
                "title"     : "",
                "introduce1": "卓贝环保科技江苏有限公司是一家环保全产业链综合服务企业，注册资金1000万，坐落于“中国环保之乡”宜兴。主要从事环保管家服务、建设项目环境影响评估、环保验收、项目立项咨询、环保政策咨询、环境应急预案编制、可行性研究报告编制、企业排污许可证代办、企业清洁生产审核、环保设备销售等业务。本着“以市场为目标、以技术为先导、以资本为支撑、以资源合成为核心”的发展理念，为广大客户提供环保一站式服务平台，现已成为长三角地区知名的环保服务企业。",
                "introduce2": "公司自成立以来，一直致力于打造一支技术精湛、服务专业、勇于奉献的技术团队，公司现有环境影响评价工程师12人，均出自国内知名高等院校，专业涵盖环境科学、环境工程、水文地质、化学、土壤学等。",
                "introduce3": "公司始终坚持“推动环境可持续发展、解决企业环保难题”的从业宗旨；坚持以客户为中心，以技术实力为根本，坚持实事求是，坚持客观公正。"
            }


        }
    }
</script>

<style scoped>
    .root {
        /*background: rgba(245, 243, 246, 0.28);*/
    }
    .maincenter {
        width      : 1200px;
        height     : 827px;
        display    : block;
        margin     : 0 auto;
        background : white;
        position   : relative;
    }
    .entitle {
        left     : 77px;
        top      : 126px;
        width    : 614px;
        height   : 53px;
        position : absolute;
        z-index  : 106;
    }
    .cstlayer {
        left       : 0px;
        top        : 135px;
        width      : 2px;
        height     : 35px;
        position   : absolute;
        z-index    : 110;
        background : black;
    }
    .wp-title_content {
        border-width  : 0px;
        border-color  : transparent;
        padding       : 0px;
        width         : 614px;
        height        : 53px;
        display       : block;
        -ms-word-wrap : break-word;
    }
    .titlespan {
        display        : block;
        color          : rgb(34, 34, 34);
        text-transform : uppercase;
        font-family    : 微软雅黑;
        font-size      : 36px;
        text-align     : left;
    }
    .js {
        left        : 77px;
        top         : 278px;
        width       : 679px;
        height      : 278px;
        position    : absolute;
        z-index     : 102;
        text-align  : left;
        color       : rgb(85, 85, 85);
        line-height : 220%;
        font-family : 微软雅黑;
        font-size   : 14px;
    }
    .introimg {
        left     : 809px;
        top      : 279px;
        width    : 391px;
        height   : 213px;
        position : absolute;
        z-index  : 109;
    }
    .oalist {
        width           : 1200px;
        height          : 153px;
        /*outline: 1px solid red;*/
        position        : absolute;
        left            : 0;
        top             : 616px;
        display         : flex;
        flex-flow       : row wrap;
        justify-content : space-around;
        align-items     : center;
        /*     display: flex;*/
        /*     flex-flow: column wrap;*/
        /*     justify-content: center;*/
        /*     align-items: center;*/
        display         : none;
    }
    .introlist {
        width       : 233px;
        height      : 153px;
        line-height : 153px;
        /*background: linear-gradient(to bottom, rgba(66, 185, 131, 0.2), rgba(19, 155, 72, 0.17));*/
        position    : relative;
    }
    .itroicon {
        display  : block;
        position : absolute;
        /*width: 48px;*/
        /*height: 46px;*/
        left     : 0;
        top      : 38px;
    }
    .intonum {
        text-align  : left;
        font-size   : 57px;
        line-height : 57px;
        display     : block;
        left        : 58px;
        top         : 34px;
        height      : 50px;
        /*width: 200px;*/
        /*background: #ff000052;*/
        position    : absolute;
        cursor      : pointer;
        color       : rgb(85, 85, 85);
        font-family : simsun;
    }
    .intonum:hover {
        color : #00987a;
    }
    .add {
        font-size : 20px;
        position  : absolute;
        right     : -15px;
        top       : -22px;
    }
    .span1 {
        position    : absolute;
        left        : 65px;
        top         : 93px;
        font-size   : 13px;
        line-height : 13px;
    }
    .span2 {
        position    : absolute;
        left        : 65px;
        top         : 110px;
        font-size   : 13px;
        line-height : 13px;
    }

</style>
