<template>
  <div class="applicationmode">{{ msg || "Default Application Mode" }}</div>
</template>

<script>
export default {
  name: 'ApplicationMode',
  props: {
    msg: String
  }
}
</script>

<style module>
.applicationmode {
  font-family: Tahoma, Arial, Verdana, sans-serif;
  font-size: 1em;
  text-align: center;
  background: cyan;
}
</style>
