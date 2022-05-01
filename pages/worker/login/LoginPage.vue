<template>
  <div id="worker-top">
    <WorkerTopHeader />
    <div class="login">
      <h2>ユーザーログイン</h2>
    </div>
  </div>
</template>

<script>

import WorkerTopHeader from "@/components/worker/top/WorkerTopHeader.vue";

export default {
  components: {
    WorkerTopHeader,
  }
}
</script>