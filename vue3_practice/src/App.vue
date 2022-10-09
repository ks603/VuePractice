<template>
  <h1 v-if="isShowing" v-html="title"></h1>
  <h3 v-else-if="isShowing === null">This is v-else-if</h3>
  <h2 v-else>This is the v-else part</h2>
  <p> something else </p>
</template>

<script>
export default {
  data(){
    return {
      title: "Heyy Vue3",
      isShowing: true,
    };
  },
};
</script>

 