<template>
  <div>
    <h1>Hello</h1>
    <h2>{{name}}</h2>

    <button @click="add">+</button>
    <h4>{{num}}</h4>
    <button @click="sub">-</button>

  </div>
</template>

<script>
  export default {
    data() {
      return {
        num: 0,
        name: '蜡笔小新'
      }
    },
    methods: {
      add() {
        this.num++;
      },
      sub() {
        this.num--;
      }

    }

  }
</script>

<style scoped>

</style>