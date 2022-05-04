<template>
  <div id="container">
    <WorkerApplication />
  </div>
</template>

<script>
import WorkerApplication from "@/components/worker/application/Application.vue";

export default {
  name: 'worker-application',
  components: {
    WorkerApplication
  }
}
</script>