<template>
  <div id="top-header">
    <div class="logo"><router-link to="/"><img src="" alt="Logo" class="header__logo"></router-link></div>
    <nav class="nav">
      <router-link to="/worker/register">会員登録(無料)</router-link>
      <router-link to="/worker/login">ログインする</router-link>
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