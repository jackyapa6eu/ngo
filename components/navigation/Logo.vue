<template>
  <h1>
    {{ title }}
  </h1>
</template>

<script>
  export default {
    props: {
      title: {
        type: String,
        default: 'Default'
      }
    }
  }
</script>

<style scoped>

</style>
