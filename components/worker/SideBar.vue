<template>
  <div id="sidebar">
    <nav class="nav">
      <ul class="ul">
        <li class="li dashboard" :class="{ active: dashboardActive }">
          <router-link to="dashboard">ダッシュボード</router-link>
        </li>
        <li class="li profile" :class="{ active: profileActive }">
          <router-link to="profile">プロフィール</router-link>
        </li>
        <li class="li list" :class="{ active: listActive }">
          <router-link to="list">案件一覧</router-link>
        </li>
        <li class="li application" :class="{ active: applicationActive }">
          <router-link to="application">応募管理</router-link>
        </li>
        <li class="li message" :class="{ active: messageActive }">
          <router-link to="message">メッセージ</router-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {
      dashboardActive: false,
      profileActive: false,
      listActive: false,
      applicationActive: false,
      messageActive: false,
    }
  },
  mounted() {
    // console.log(this.$route.path)
    if(this.$route.path === '/worker/dashboard') {
      this.dashboardActive = true;
    } else if(this.$route.path === '/worker/profile') {
      this.profileActive = true;
    } else if(this.$route.path === '/worker/list') {
      this.listActive = true;
    } else if(this.$route.path === '/worker/application') {
      this.applicationActive = true;
    } else if(this.$route.path === '/worker/message') {
      this.messageActive = true;
    }
  }
}
</script>