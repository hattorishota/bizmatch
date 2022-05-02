<template>
  <div id="register">
    <CompanyTopHeader />
    <div class="auth">
      <div class="wrap">
        <h2 class="title">ログイン画面</h2>
        <form action="" class="form">
          <div class="box1">
            <label class="name">メールアドレス</label>
            <div class="input">
              <input type="text">
            </div>
          </div>
          <div class="box1">
            <label class="name">パスワード</label>
            <div class="input">
              <input type="text">
            </div>
          </div>
          <div class="box1">
            <router-link to="/company/dashboard" class="btn check">ログインする</router-link>
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