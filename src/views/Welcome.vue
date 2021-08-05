<template>
  <div>{{$route.meta.title}}</div>
</template>

<script>
export default {
  name: "welcome",
  mounted() {
    console.log("环境变量和模式", import.meta.env);
  }
};
</script>

<style lang="scss">
</style>
