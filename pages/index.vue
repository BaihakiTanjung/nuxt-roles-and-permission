<template>
  <h1>index</h1>
</template>
<script>
export default {
  middleware: 'authenticated',
  mounted() {
    console.log(this.$auth)
    console.log(this.$auth.hasScope('admin'))
  }
}
</script>
