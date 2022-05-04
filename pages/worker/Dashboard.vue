<template>
  <div id="container">
    <WorkerDashboard />
  </div>
</template>

<script>
import WorkerDashboard from "@/components/worker/dashboard/Dashboard.vue";

export default {
  name: 'worker-dashboard',
  components: {
    WorkerDashboard
  }
}
</script>