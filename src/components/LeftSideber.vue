<template>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
</template>

<script>
export default {
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
