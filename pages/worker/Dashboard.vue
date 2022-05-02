<template>
  <div id="worker-dashboard">
    <WorkerTopHeader />
    <div class="wrapper">
      ダッシュボード
    </div>
    <TopFooter />
  </div>
</template>

<script>
import TopFooter from "@/components/TopFooter.vue";
import WorkerTopHeader from "@/components/worker/top/WorkerTopHeader.vue";
// import WorkerDashboard from "@/components/worker/dashboard/";

export default {
  name: 'WorkerRegister',
  components: {
    WorkerTopHeader,
    TopFooter,
    // WorkerDashboard,
  }
}
</script>