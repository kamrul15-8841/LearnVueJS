<template>
    <h1>my name is {{name}} and my superhero  is {{herroName}}</h1>
  
</template>

<script>
    export default {
        name: 'KamrulHello',
        props: ['name','herroName']
    }
</script>

<style scoped>

</style>