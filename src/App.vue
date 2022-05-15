<template>
<h1>{{title}}</h1>
<input type="text" ref="name">
<button @click="handleClick">Come on, click me</button>
</template>

<script>

export default {
  name: 'App',
  data(){
    return {
      title: 'Portfolio project start me upppppp'
    }
  },
  methods: {
    handleClick() {
      console.log(this.$refs.name)
    }
  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
