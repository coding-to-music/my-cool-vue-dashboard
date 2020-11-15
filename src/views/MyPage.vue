
<template>
  <div class="myPage page">
    <h3 class="back-btn" @click="$router.push('/')">< back to article</h3>
    <grid />
    <h3 class="back-btn" @click="$router.push('/')">< back to article</h3>
  </div>
</template>

<script>
import Grid from '@/components/grid/Grid'
export default {
  name: 'MyPage',
  components: {
    'grid': Grid
  }
}
</script>

<style lang="scss">
@import "./../styles/variables";

.page.myPage {
  .back-btn {
    cursor: pointer;
  }
}
</style>
