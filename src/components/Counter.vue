<template>

  <h1>0:0:{{counter}}</h1>
  <button @click="start" class="ring-4 ring-indigo-300">
    Increment Counter
  </button>
</template>

<script>
export default {
  name: 'Counter',
  props: {
  },
  data() {
    return {
      counter: 0
    }
  },
  methods: {
    start() {
      this.counter = this.counter + 1;
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
