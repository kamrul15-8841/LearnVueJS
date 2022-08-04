<template>
<h2>{{name}}</h2>
<div>
  <button v-on:click="chacgeName($event),increment(1,$event)">Change Name</button>
</div>
<h2>{{count}}</h2>
<div>
  <button @click="increment(1)">Increment1</button>
  <button @click="decrement(1)">Decrement</button>
  <button @click="increment(2)">Decrement2</button>
  <button @click="decrement(2)">Decrement2</button>
</div>
</template>

<script>


export default {
  name:'app',
  data() {
    return {
      name: 'Kamrul',
      count:0,
    };
  },
  methods: {
    chacgeName(){
      this.name = "Md. Kamrul Hasan"
      console.log('Event',event)
    },
    increment(num){
      this.count += num
      console.log('Event',event)
    },
    decrement(num){
      this.count -= num
      console.log('Event',event)
    }
  },
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
