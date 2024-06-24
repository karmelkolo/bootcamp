<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Hello<br>
    {{ counter }}<br>
    <button @click="countup">Add</button>
  </main>
</template>

<script>
export default{
  data(){
    return{
      counter: 0
    }
  },
  methods: {
    countup(){
      this.counter++
    }
  }
}
</script>
