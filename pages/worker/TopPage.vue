<template>
  <div id="worker-top">
    <TopHeader />
    <section class="section1">
      <div class="wrap">
        <div class="bg-wrap">
          <img :src="bgImg1" alt="">
        </div>
        <div class="txt-wrap">
          <h2 class="leading">高単価なリモート案件で自由に仕事を</h2>
          <div class="txt-box1">
            <p class="txt">SIer・SESから自社サービス</p>
            <p class="txt">ITコンサルタントへの転職実績多数！</p>
            <p class="txt">ITエンジニア案件を継続提案し、</p>
            <p class="txt">フリーランスの安定収入をサポートします。</p>
          </div>
        </div>
        <div class="flex">
          <div class="btn-wrap blue">
            <router-link to="/worker/auth/registerinput">無料会員登録</router-link>
          </div>
          <div class="btn-wrap">
            <router-link to="/worker/login/loginpage">ログインする</router-link>
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
          <h2 class="title">フリーランスエンジニアの皆さんのお悩み解決します</h2>
          <span class="sub-title">Bizmatchなら自分のスキル/レベルに合う案件が見つかる！</span>
        </div>
        <ul class="ul">
          <li class="li">
            <img :src="itemImg1" alt="" class="img">
            <p class="leading">
              キャリア・スキルアップに<br>
              繁がる案件も多数
            </p>
            <p class="txt">キャリア形成を重要視し、単に案件を紹介するのではなく、1人1人が望むキャリアの実現をサポートします。</p>
          </li>
          <li class="li">
            <img :src="itemImg2" alt="" class="img">
            <p class="leading">
              上流~開発工程まで<br>
              豊富な案件が揃っています
            </p>
            <p class="txt">これまで蓄積されてきたご経験と現在のご関心、仕事内容のご意向、そして今後のキャリア像を面談時に伺った上で上流~開発工程まで取り揃えた案件をご紹介いたします。</p>
          </li>
          <li class="li">
            <img :src="itemImg3" alt="" class="img">
            <p class="leading">高待遇案件が多数</p>
            <p class="txt">平均報酬80万円以上をご紹介。稼働月当月末締め翌月15日にお支払いいたします。</p>
          </li>
        </ul>
      </div>
    </section>
    <section class="ad">
      <p class="txt">まずは以下から会員登録をしてみましょう！</p>
      <div class="btn-box">
        <router-link to="/worker/auth/registerinput">無料会員登録する</router-link>
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
import Item1 from "@/assets/images/worker/item_1.jpg"
import Item2 from "@/assets/images/worker/item_2.jpg"
import Item3 from "@/assets/images/worker/item_3.jpg"

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