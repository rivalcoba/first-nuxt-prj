<template>
  <div class="container">
    <the-nav-bar />
    <Nuxt />
  </div>
</template>
<script>
import TheNavBar from '@/components/TheNavBar.vue';
export default {
  componets: {
    'the-nav-bar': TheNavBar
  }
}
</script>