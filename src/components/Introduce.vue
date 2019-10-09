<template>
    <div class="root">
        <div class="maincenter">
            <span class="cstlayer"> </span>
            <div id="" type="title" class="entitle ">
                <div class="wp-title_content">
                    <span class="titlespan"><strong>Overview of Enterprises</strong></span>
                    <span class="titlespan" style="font-size: 30px">企业概况</span>
                </div>
            </div>
            <div class="js">
                <p>{{introduce1}}</p>
                <p>{{introduce2}}</p>
                <p>{{introduce3}}</p>
            </div>
            <img src="../assets/images/mou.png" class="introimg" alt="">
        </div>
    </div>

</template>

<script>
    export default {
        name: "introduce",
        data() {
            return {
                "title": "",
                "introduce1": "卓贝环保科技江苏有限公司是一家环保全产业链综合服务企业，主要从事环保管家服务、建设项目环境影响评估、环保工程设计、环境技术咨询、环保验收、环境应急预案、可行性研究报告编制、排污许可证办理、企业清洁生产审核、环保设备销售等业务。 ",
                "introduce2": "本着“以市场为目标、以技术为先导、以资本为支撑、以资源合成为核心”的发展理念，为广大客户提供环保一站式服务平台，现已成为长三角地区知名的环保服务企业。",
                "introduce3": "公司自成立以来，一直致力于打造一支技术精湛、服务专业、勇于奉献的技术团队，公司现有注册环境影响评价工程师22人，均出自国内知名高等院校，专业涵盖环境科学、环境工程、水文地质、化学、土壤学等。公司始终坚持“推动环境可持续发展、解决企业环保难题”的从业宗旨；坚持以客户为中心，以技术实力为根本，坚持实事求是，坚持客观公正。"
            }
        }
    }
</script>

<style scoped>
    .root {
        background: rgba(245, 243, 246, 0.28);
    }

    .maincenter {
        width: 1200px;
        height: 827px;
        display: block;
        margin: 0 auto;
        background: white;
        position: relative;

    }

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

    .js {
        left: 77px;
        top: 278px;
        width: 679px;
        height: 278px;
        position: absolute;
        z-index: 102;
        text-align: left;
        color: rgb(85, 85, 85);
        line-height: 220%;
        font-family: 微软雅黑;
        font-size: 14px;
    }

    .introimg {
        left: 809px;
        top: 279px;
        width: 391px;
        height: 213px;
        position: absolute;
        z-index: 109;
    }

</style>
