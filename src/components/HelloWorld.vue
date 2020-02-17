<template>
  <div class="hello">
    <span v-text="value"></span>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    value: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
