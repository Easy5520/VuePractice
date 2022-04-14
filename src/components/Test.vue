<template>
  <div>
    <button @click="isShow = !isShow">显示/隐藏</button>
    <h1 v-show="isShow">h`h`h`hello</h1>
  </div>
</template>

<script>
export default {
  name: "Test",
  data() {
    return {
      isShow: true,
    };
  },
};
</script>

<style scoped>
h1 {
  background-color: coral;
}
</style>