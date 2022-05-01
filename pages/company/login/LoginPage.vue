<template>
  <div id="company-top">
    <CompanyTopHeader />
    <div class="login">
      <h2>ユーザーログイン</h2>
    </div>
  </div>
</template>

<script>

import CompanyTopHeader from "@/components/company/top/CompanyTopHeader.vue";

export default {
  components: {
    CompanyTopHeader,
  }
}
</script>