<template>
  
    <h2>{{title}} Like- {{likes}} </h2>
 
</template>

<script>
    export default {
        name:'ArticleText',
        props: {
            title: String,
            likes: Number
        }
    }
</script>

<style scoped>

</style>