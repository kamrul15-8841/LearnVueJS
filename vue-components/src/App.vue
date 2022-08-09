<template>


<ArticleText title="Article title" :likes="501"/>

</template>

<script>
//import KamrulHello from "./components/KamrulHello.vue";
import ArticleText from "./components/ArticleText.vue";


export default {
    name: "App",
    components: {
      // KamrulHello,  
       ArticleText },
    data() {
      return {
        name: 'Md. Kamrul Hasan',
        herroname: 'Man Of Steel'
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
