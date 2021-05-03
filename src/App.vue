<template>
  <div class="container">
<div class="row justify-content-center">
      <Card class="bg-primary mr-2"/>
      <Card class="bg-success mr-2"/>
      <Card class="bg-dark mr-2"/>
</div>
  </div>
</template>

<script>
import Card from '@/components/Card'

export default {
  name: 'App',
  components: {
    Card,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
