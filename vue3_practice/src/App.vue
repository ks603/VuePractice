<template>
  <ul>
    <h1>DC Heroes</h1>
    <li v-for="(value, index) in dcHeros" :key="value.id">{{ index }}{{ value }} {{ key }}</li>
  </ul>
</template>


<script>
export default {
  data() {
    return {
      dcHeros: {SuperGirl: 'SuperGirl', Flash: 'Flash',Batman: 'Batman', Arrow: 'Arrow', SuperMan: 'SuperMan'},
    }
  }
}
</script>

<style>

</style>