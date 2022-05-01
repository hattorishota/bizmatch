<template>
  <div id="top">
    <TopHeader />
    <div class="fv">
      <img :src="fvImg" alt="">
    </div>
  </div>
</template>

<script>
import TopHeader from "../frontpage/TopHeader.vue";
import Fv1 from "@/assets/images/fv/fv_1.jpg"

// setting Swiper

// setting module

export default {
  data() {
    return {
      fvImg: Fv1,
    };
  },
  components: {
    TopHeader,
  }
};
</script>