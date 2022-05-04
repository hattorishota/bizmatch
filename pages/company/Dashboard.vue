<template>
  <div id="worker-dashboard">
    <WorkerTopHeader />
    <div class="wrapper">
      <SideBar />
      <section class="section">
        <h2>ダッシュボード</h2>
      </section>
    </div>
    <TopFooter />
  </div>
</template>

<script>
import TopFooter from "@/components/TopFooter.vue";
import WorkerTopHeader from "@/components/worker/top/WorkerTopHeader.vue";
import SideBar from "@/components/worker/SideBar.vue";
// import WorkerDashboard from "@/components/worker/dashboard/";

export default {
  name: 'WorkerRegister',
  components: {
    WorkerTopHeader,
    TopFooter,
    SideBar,
    // WorkerDashboard,
  }
}
</script>