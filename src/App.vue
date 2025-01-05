<template>
  <div>
    {{ message }}
    <button @click="showAlert">클릭</button>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        message : 'hi'
      }
    },
    methods : {
      showAlert() {
        alert('hello')
      }
    }
  }
</script>

<style scoped>

</style>