<template>
  <div id="register">
    <WorkerTopHeader />
    <div class="auth">
      <div class="wrap">
        <h2 class="title">ログイン画面</h2>
        <form action="" class="form" @submit.prevent="loginUser">
          <div class="box1">
            <label class="name" for="email">メールアドレス</label>
            <div class="input">
              <input type="text" v-model="user.email">
            </div>
          </div>
          <div class="box1">
            <label class="name" for="password">パスワード</label>
            <div class="input">
              <input type="password" v-model="user.password">
            </div>
          </div>
          <div class="box1">
            <router-link to="/worker/dashboard" class="btn check">ログインする</router-link>
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
  data(){
    return {
      user:{
        email:'',
        password:''
      }
    }
  },
  components: {
    WorkerTopHeader,
    TopFooter,
  },
  methods:{
    loginUser(){
      this.$auth.loginWith('local',{
        data:this.user
      })
    },
  }
}
</script>