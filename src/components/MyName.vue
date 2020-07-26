<template>
  <div>
    <h1>Hello, My name is <strong>{{ name }}</strong>. </h1>

  </div>
</template>

<script>
  export default {
    props: ['name']
  }
</script>

<style scoped>
h1 {
  font-weight: 300; 
}
</style>