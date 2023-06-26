<template>
  <SecurityBanner  msg="Security Banner" />
</template>


<script>
import SecurityBanner from './SecurityBanner.vue'

export default {
  name: 'Footer',
  components: {
    SecurityBanner
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
