<template>
    <div class="container">
      {{ number }}
      {{ stick }}
    </div>
</template>

<script>
export default {
  name: 'BaseCard',
  data () {
    return {
      numbers: '4',
      sticks: 'caca'
    }
  },
  props: {
    number: {
      type: Number
    },
    stick: {
      type: String
    }
  },
  method: {
    getNumber: () => { return (Math.floor(Math.random) * 6) }
  }
}
</script>

<style scoped>
    .container {
      height: 350px;
      width: 300px;
      background: white;
      border-radius: 15px 15px 15px 15px;
      border-color: black;
      border-style: solid;
      margin: auto;
    }
</style>
