<template>
  <div class="banner" >{{msg || "Banner" }}</div>
</template>

<script>
export default {
  name: 'Banner',
  props: {
    msg: String,
    bannercolor: String
  }
}
</script>

<style>
.banner {
  font-family: Tahoma, Arial, Verdana, sans-serif;
  font-size: 1rem;
  font-weight: bold;
  text-align: center;
  background: green;
}
</style>
