<template>
  <div id="worker-profile">
    <WorkerTopHeader />
    <div class="wrapper">
      <SideBar />
      <section class="section">
        <h2>プロフィール</h2>
      </section>
    </div>
    <TopFooter />
  </div>
</template>

<script>
import TopFooter from "@/components/TopFooter.vue";
import WorkerTopHeader from "@/components/worker/top/WorkerHeader.vue";
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