<template>
  <div id="app">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      msg: 'hello1'
    }
  },
  mounted() {
    window.vue = this
    console.log(this.msg)
    console.log(this._data.msg)
  }
}
</script>

<style>

</style>
