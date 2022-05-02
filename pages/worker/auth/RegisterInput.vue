<template>
  <div id="register">
    <WorkerTopHeader />
    <div class="auth">
      <div class="wrap">
        <h2 class="title">会員登録画面</h2>
        <form action="" class="form">
          <div class="box1">
            <label class="name">氏名</label>
            <div class="input">
              <input type="text">
            </div>
          </div>
          <div class="box1">
            <label class="name">フリガナ</label>
            <div class="input">
              <input type="text">
            </div>
          </div>
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
            <label class="name">パスワード（確認用）</label>
            <div class="input">
              <input type="text">
            </div>
          </div>
          <div class="box1">
            <label class="name">電話番号</label>
            <div class="input">
              <input type="text">
            </div>
          </div>
          <div class="box1">
            <router-link to="/worker/auth/registercheck" class="btn check">確認する</router-link>
          </div>
        </form>
      </div>
    </div>
    <TopFooter />
  </div>
</template>

<script>
import TopFooter from "@/components/TopFooter.vue";
import WorkerTopHeader from "@/components/worker/top/WorkerTopHeader.vue";

export default {
  name: 'WorkerRegister',
  components: {
    WorkerTopHeader,
    TopFooter,
  }
}
</script>