<template>
  <div id="top-header">
    <div class="logo"><router-link to="/"><img :src="logoImg" alt="Logo" class="header__logo"></router-link></div>
    <nav class="nav">
      <router-link to="worker/TopPage">ユーザーはこちら</router-link>
      <router-link to="company/TopPage">企業様はこちら</router-link>
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