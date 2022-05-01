<template>
  <div id="worker-register">
    <WorkerTopHeader />
    <div class="auth">
      <h2>ユーザー会員登録画面</h2>
    </div>
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