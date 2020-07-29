<template>
  <div class="welcome">
    <h1>{{ name }}</h1>
  </div>
</template>

<script>
export default {
  name: 'MyName',
  props: {
    name: String
  }
}
</script>

<style scoped>
h1 {
  margin: 40px 0 0;
}
</style>