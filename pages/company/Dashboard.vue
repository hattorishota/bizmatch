<template>
  <div id="worker-dashboard">
    <CompanyTopHeader />
    <div class="wrapper">
      ダッシュボード
    </div>
    <TopFooter />
  </div>
</template>

<script>
import TopFooter from "@/components/TopFooter.vue";
import CompanyTopHeader from "@/components/company/top/CompanyTopHeader.vue";
// import WorkerDashboard from "@/components/worker/dashboard/";

export default {
  name: 'WorkerRegister',
  components: {
    CompanyTopHeader,
    TopFooter,
    // WorkerDashboard,
  }
}
</script>