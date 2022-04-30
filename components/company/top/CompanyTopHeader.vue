<template>
  <div id="top-header">
    <div class="logo"><router-link to="/"><img :src="logoImg" alt="Logo" class="header__logo"></router-link></div>
    <nav class="nav">
      <router-link to="/company/auth/register">会員登録(無料)</router-link>
      <router-link to="/company/login/loginpage">ログインする</router-link>
    </nav>
  </div>
</template>

<script>
import LogoImg from '~/assets/images/logo/logo.png'

export default {
  data() {
    return {
      logoImg: LogoImg,
    };
  },
  computed: {


  }
}
</script>