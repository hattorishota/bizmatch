<template>
  <div id="company-top">
    <TopHeader />
    <section class="section1">
      <div class="wrap">
        <div class="bg-wrap">
          <img :src="bgImg1" alt="">
        </div>
        <div class="txt-wrap">
          <h2 class="leading">
            優秀なエンジニアと出会える<br>
            新時代の採用プラットフォーム
          </h2>
          <div class="txt-box1">
            <p class="txt">「エンジニアの採用がうまくいかない・・」</p>
            <p class="txt">「急にエンジニアが辞めてしまった・・」</p>
            <p class="txt">「チーム体制で参画できるエンジニアがいない・・」</p>
            <p class="txt">そんな課題を<span class="blue"> Bizmatch </span>が解決します。</p>
          </div>
        </div>
        <div class="flex">
          <div class="btn-wrap blue">
            <router-link to="/company/auth/registerinput">無料会員登録</router-link>
          </div>
          <div class="btn-wrap">
            <router-link to="/company/login/loginpage">ログインする</router-link>
          </div>
        </div>
      </div>
    </section>
    <section class="section2">
      <img :src="bgImg2" alt="">
    </section>
    <section class="section3">
      <div class="wrap">
        <div class="title-box">
          <h2 class="title">ご紹介できる人材</h2>
          <span class="sub-title">Bizmatchならその時欲しいエンジニアが見つかる！</span>
        </div>
        <ul class="ul">
          <li class="li">
            <img :src="itemImg1" alt="" class="img">
            <p class="leading">PM経験者</p>
          </li>
          <li class="li">
            <img :src="itemImg2" alt="" class="img">
            <p class="leading">Webエンジニア</p>
          </li>
          <li class="li">
            <img :src="itemImg3" alt="" class="img">
            <p class="leading">CTOクラス</p>
          </li>
        </ul>
      </div>
    </section>
    <section class="ad">
      <p class="txt">まずは以下から会員登録をしてみましょう！</p>
      <div class="btn-box">
        <router-link to="/company/auth/registerinput">無料会員登録する</router-link>
      </div>
    </section>
    <TopFooter />
  </div>
</template>

<script>
import TopHeader from "@/components/worker/top/WorkerTopHeader.vue";
import TopFooter from "@/components/TopFooter.vue";
import BgImg1 from "@/assets/images/common/arrow1.png"
import BgImg2 from "@/assets/images/worker/bg_1.jpg"
import Item1 from "@/assets/images/company/top/designer.jpg"
import Item2 from "@/assets/images/company/top/coder.jpg"
import Item3 from "@/assets/images/company/top/manager.jpg"

export default {
  data() {
    return {
      bgImg1: BgImg1,
      bgImg2: BgImg2,
      itemImg1: Item1,
      itemImg2: Item2,
      itemImg3: Item3,
    };
  },
  components: {
    TopHeader,
    TopFooter,
  }
}
</script>