<template>
    <div>
        <div class="swiper-container swiperimg" id="headswiper">
            <div class="swiper-wrapper wrapper">
                <div class="swiper-slide" v-for="(item,index) in swiper" :key="index">
                    <img :src="item" class="headswiperbg" alt="">
                </div>
                <div class="swiper-slide">
                    <img src="../assets/images/bg1.jpg" class="headswiperbg" alt="">
                </div>
            </div>
            <div class="swiper-pagination"></div>
        </div>
        <img src="../assets/images/left_arrow.png" class="arrow leftarrow" alt="">
        <img src="../assets/images/right_arrow.png" class="arrow rightarrow" alt="">
    </div>
</template>
<script>
    import Swiper from "swiper"
    import "swiper/css/swiper.min.css"

    export default {
        name: "Swiperimg",
        data() {
            return {
                swiper: [
                    require('@/assets/images/bg1.jpg'),
                    require('@/assets/images/bg2.jpg'),
                    require('@/assets/images/bg3.jpg')
                ]
            }
        },
        mounted() {
            var mySwiper = new Swiper('#headswiper', {
                autoplay: {
                    delay: 3000,
                    stopOnLastSlide: true
                },
                navigation: {
                    nextEl: '.leftarrow',
                    prevEl: '.rightarrow',
                },
                pagination: {
                    el: '.swiper-pagination',
                    clickable: true,
                },
                loop: true,
                observer: true,
            });
        }
    }
</script>
<style>
    #headswiper .swiper-pagination-bullet {
        margin: 0 4px;
        width: 46px;
        height: 5px;
        border-radius: 0;
        /*background: #139b48;*/
    }

    #headswiper .swiper-pagination-bullet-active {
        background: #139b48;
    }
</style>
<style scoped>

    .swiperimg, .headswiperbg {
        width: 100%;
        height: 100%;
    }

    .wrapper {
        position: relative;
    }

    .arrow {
        width: 50px;
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        z-index: 100;
        cursor: pointer;
    }

    .leftarrow {
        left: 2%;
    }

    .rightarrow {
        right: 2%;
    }

    .swiper-slide {
        overflow: hidden;
    }
</style>
