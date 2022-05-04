<template>
  <div id="container">
    <WorkerList />
  </div>
</template>

<script>
import WorkerList from "@/components/worker/list/List.vue";

export default {
  name: 'worker-list',
  components: {
    WorkerList
  }
}
</script>