<template>
  <div>
      <h3>App组件</h3>
      <MyNews></MyNews>
      <hr>
      <MyStudy></MyStudy>
  </div>
</template>

<script>
  import MyNews from './MyNews'
import MyStudy from './components/MyStudy.vue';
export default {
  components: { MyNews, MyStudy },
    name:"App"
  }
</script>

<style lang="scss" scoped>

</style>