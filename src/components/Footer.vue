<template>
    <div class="footer">
        <div class="logoarea">
            <img src="../assets/images/logo.png" style="width: 135px" alt="">
            <!--            <p>卓贝环保科技江苏有限公司</p>-->
        </div>
        <div class="mianbox">
            <div class="abtinfo cell">
                <img src="../assets/images/phone.png" class="phone" alt="">
                <p class="desc">
                    <span>{{cell1}}</span> <br/>
                    <span> {{cell2}} </span>
                </p>
            </div>
            <div class="abtinfo addr">
                <img src="../assets/images/address.png" class="phone" alt="">
                <p class="desc">
                    <span>地址</span> <br/>
                    <span>{{address}}</span>
                </p>
            </div>
            <div class="abtinfo Email">
                <img src="../assets/images/email.png" class="phone" alt="">
                <p class="desc">
                    <span>邮件</span> <br/>
                    <span>{{email}}</span>
                </p>
            </div>
        </div>
        <div class="abtsite">
            <!--            增值电信业务经营许可证： 鲁00-0000XXXX 网络文化经营许可证：鲁网文[0000]0000-XXX号 COPYRIGHT© 2003-2020 XXXX 版权所有-->
            COPYRIGHT© 2019-2020 卓贝环保科技江苏有限公司 版权所有 Jiangsu Zowbei EP Technology CO., LTD.
        </div>
    </div>
</template>

<script>
    export default {
        name: "Footer",
        data() {
            return {
                cell1  : "客服: 0510-87278086",
                cell2  : "檀经理:  18019244190",
                address: "江苏省宜兴市官林镇戈潘路28号",
                address: "江苏省宜兴市官林镇戈潘路28号",
                email  : "jinzpg@163.com"
            }
        }
    }
</script>


<style rel="stylesheet/scss" lang="scss" scoped>
    .footer {
        width: 100%;
        height: 380px;
        background: #002538;
        .logoarea {
            width: 1200px;
            height: 305px;
            display: block;
            display: flex;
            margin: 0 auto;
            flex-flow: column nowrap;
            justify-content: center;
            align-items: center;
        }
        .mianbox {
            /*background: red;*/
            width: 1200px;
            height: 60px;
            display: flex;
            margin: 0 auto;
            flex-flow: row nowrap;
            justify-content: space-evenly;
            align-items: flex-end;
            .abtinfo {
                width: 25%;
                height: 50px;
                box-sizing: border-box;
                display: flex;
                margin-bottom: 25px;
                flex-flow: row nowrap;
                justify-content: space-evenly;
                align-items: center;
                color: #d6d3d3;
                font-size: 15px;
                .desc {
                    text-align: justify;
                    padding-left: 15px;
                    text-align: justify;
                    width: 80%;
                }
            }
        }
        .abtsite {
            width: 100%;
            background: rgb(0, 27, 40);
            height: 60px;
            line-height: 60px;
            color: #a2a2a1;
            font-size: 12px;
        }
    }

</style>