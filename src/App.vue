<template>
  <div id="app">
    <h1>Hello {{ name }}</h1>
    <button @click="changeName">Change name</button>
  </div>
</template>

<script>
export default {
  name: 'app',
  data() {
    return {
      name: 'world'
    }
  },
  methods: {
    changeName() {
      this.name = 'Vasya'
    }
  }
}
</script>
