<template>
  <div id="top-header">
    <div class="logo"><router-link to="/"><img :src="logoImg" alt="Logo" class="header__logo"></router-link></div>
    <nav class="nav">
      <router-link to="/company/register">会員登録(無料)</router-link>
      <router-link to="/company/login">ログインする</router-link>
    </nav>
  </div>
</template>

<script>

export default {
  data() {
    return {

    };
  },
  computed: {

  }
}
</script>