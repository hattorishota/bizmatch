<template>
  <div id="worker-register">
    <WorkerTopHeader />
    <h2>ユーザー会員登録画面</h2>
  </div>
</template>

<script>

import WorkerTopHeader from "@/components/worker/top/WorkerTopHeader.vue";

export default {
  name: 'WorkerRegister',
  components: {
    WorkerTopHeader,
  }
}
</script>