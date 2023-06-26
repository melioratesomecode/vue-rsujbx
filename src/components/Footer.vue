<template>
  <Banner  msg="Banner" />
</template>


<script>
import Banner from './Banner.vue'

export default {
  name: 'Footer',
  components: {
    Banner
  },
  props: {
    title: String,
    bannercolor: String
    }
}
</script>

<style>
  font-family: Tahoma, Arial, Verdana, sans-serif;
  font-size: 1em;
  font-weight: bold;
  text-align: center;
</style>
