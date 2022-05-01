<template>
  <div class="page top">
    <TopPage />
  </div>
</template>

<script>
import TopPage from '~/components/frontpage/TopPage'

export default {
  name: 'IndexPage',
  target: 'static',
  components: {
    TopPage,
  }
}
</script>
