<template>
  <div id="container">
    <WorkerMessage />
  </div>
</template>

<script>
import WorkerMessage from "@/components/worker/message/Message.vue";

export default {
  name: 'worker-list',
  components: {
    WorkerMessage
  }
}
</script>