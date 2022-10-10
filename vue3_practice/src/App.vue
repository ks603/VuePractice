<template>
  <h1>DC Heroes</h1>
  <ul>
    <li v-for="num in 10" :key="num.id">{{num}}</li>
  </ul>
</template>


<script>
export default {

}
</script>

<style>

</style>