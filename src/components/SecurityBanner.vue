<template>
  <div class="securitybanner" >{{msg || "Security Banner" }}</div>
</template>

<script>
export default {
  name: 'SecurityBanner',
  props: {
    msg: String,
    bannercolor: String
  }
}
</script>

<style>
.securitybanner {
  font-family: Tahoma, Arial, Verdana, sans-serif;
  font-size: 1rem;
  font-weight: bold;
  text-align: center;
  background: green;
}
</style>
