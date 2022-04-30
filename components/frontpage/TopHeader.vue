<template>
  <div id="top-header">
    <div class="logo"><router-link to="/"><img src="" alt="Logo" class="header__logo"></router-link></div>
    <nav class="nav">
      <router-link to="/">TOP</router-link>
      <router-link to="/worker">ユーザーはこちら</router-link>
      <router-link to="/company">企業様はこちら</router-link>
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