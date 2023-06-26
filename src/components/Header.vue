<template>
  <SecurityBanner  msg="Security Banner" />
  <ApplicationMode />
  <div class="headertitle">{{ msg || "Default Title" }}</div>
</template>

<script >
import SecurityBanner from './SecurityBanner.vue'
import ApplicationMode from './ApplicationMode.vue'

export default {
  name: 'Header',
  components: {
    SecurityBanner,
    ApplicationMode
  },
  props: {
    title: String
  }
}
</script>

<style>
.headertitle {
  font-family: Tahoma, Arial, Verdana, sans-serif;
  font-size: 1em;
  font-weight: bold;
  text-align: center;
}
</style>
