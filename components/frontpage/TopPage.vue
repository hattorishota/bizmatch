<template>
  <div id="top">
    <TopHeader />
    <client-only>
      <swiper
        ref="carousel"
        class="swiper"
        :options="swiperOptions"
        @ready="onSwiperRedied"
        @clickSlide="onSwiperClickSlide"
        @slideChangeTransitionStart="onSwiperSlideChangeTransitionStart"
      >
        <swiper-slide>Slide 1</swiper-slide>
        <swiper-slide>Slide 2</swiper-slide>
        <swiper-slide>Slide 3</swiper-slide>
        <swiper-slide>Slide 4</swiper-slide>
        <swiper-slide>Slide 5</swiper-slide>
        <swiper-slide>Slide 6</swiper-slide>
        <div slot="pagination" class="swiper-pagination" />
      </swiper>
    </client-only>
  </div>
</template>

<script>
import TopHeader from "../frontpage/TopHeader.vue";

// setting Swiper

// setting module

export default {
  data() {
    return {
      swiperOptions: {
        loop: true,
        slidesPerView: '1',
        centeredSlides: true,
        spaceBetween: 30,
        pagination: {
          el: '.swiper-pagination',
          dynamicBullets: true
        }
      }
    };
  },
  components: {
    TopHeader,
  },
  methods: {
    onSwiperRedied (swiper) {
      console.log('Swiper redied!', swiper)
    },
    onSwiperSlideChangeTransitionStart () {
      console.log('SwiperSlideChangeTransitionStart!')
    },
    onSwiperClickSlide (index, reallyIndex) {
      console.log('Swiper click slide!', reallyIndex)
    }
  },
};
</script>