<template>
  <div id="top">
    <!-- <TopHeader /> -->
    <div class="fv">
      <div class="fv_box">
        <div class="img-box">
          <img :src="fvImg" alt="">
        </div>
        <div class="txt-box">
          <p class="txt1">エンジニアとして就職・転職・副業がしたいなら</p>
          <h2 class="title"><img :src="logoImg" alt=""></h2>
          <router-link to="/worker/toppage" class="anchor">求職者様はこちら</router-link>
          /
          <router-link to="/company/toppage" class="anchor">企業様はこちら</router-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import TopHeader from "../frontpage/TopHeader.vue";
import Fv1 from "@/assets/images/fv/fv_1.jpg"
import Logo1 from "@/assets/images/logo/logo-w.png"

// setting Swiper

// setting module

export default {
  data() {
    return {
      fvImg: Fv1,
      logoImg: Logo1,
    };
  },
  components: {
    // TopHeader,
  }
};
</script>