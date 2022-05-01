<template>
  <div id="top-footer">
    <h1 class="logo"><router-link to="/"><img :src="logoImg" alt="Logo" class="header__logo"></router-link></h1>
  </div>
</template>

<script>
import LogoImg from '~/assets/images/logo/logo-white.png'

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