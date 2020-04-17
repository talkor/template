<template>
  <div class="hello">
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
export default {
  props: {
    message: {
      type: String,
      default: 'Welcome'
    }
  }
};
</script>

<style scoped lang="scss">
a {
  color: #42b983;
}
</style>
