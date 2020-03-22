<template>
  <div class="subscribe">
    <img alt="Vue logo" src="../assets/logo_dav.png">
    <SubscribeForm/>
  </div>
</template>

<script>
  import SubscribeForm from '@/components/SubscribeForm.vue'

export default {
  name: 'Subscribe',
  components: {
    SubscribeForm
  }
}
</script>

<style scoped>
  img {
    margin-left: auto;
    margin-right: auto;
  }
</style>
