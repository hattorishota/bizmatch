<template>
  <div id="company-register">
    <CompanyTopHeader />
    <div class="auth">
      <div class="wrap">
        <h2 class="title">会員登録画面</h2>
        <form action="" class="form">
          <div class="box1">
            <label class="name">氏名</label>
            <div class="input">
              <p class="txt">田中太郎</p>
            </div>
          </div>
          <div class="box1">
            <label class="name">フリガナ</label>
            <div class="input">
              <p class="txt">タナカタロウ</p>
            </div>
          </div>
          <div class="box1">
            <label class="name">メールアドレス</label>
            <div class="input">
              <p class="txt">sample@gmail.com</p>
            </div>
          </div>
          <div class="box1">
            <label class="name">パスワード</label>
            <div class="input">
              <p class="txt">****</p>
            </div>
          </div>
          <div class="box1">
            <label class="name">パスワード（確認用）</label>
            <div class="input">
              <p class="txt">****</p>
            </div>
          </div>
          <div class="box1">
            <label class="name">電話番号</label>
            <div class="input">
              <p class="txt">09012345678</p>
            </div>
          </div>
          <div class="box1">
            <router-link to="/company/auth/registerinput" class="btn back">修正する</router-link>
            <router-link to="/company/dashboard" class="btn submit">送信する</router-link>
          </div>
        </form>
      </div>
    </div>
    <TopFooter />
  </div>
</template>

<script>
import TopFooter from "@/components/TopFooter.vue";
import CompanyTopHeader from "@/components/company/top/CompanyTopHeader.vue";

export default {
  name: 'WorkerRegister',
  components: {
    CompanyTopHeader,
    TopFooter,
  }
}
</script>