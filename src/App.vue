<template>
  <div>
      <h3>App组件</h3>
      <MyNews></MyNews>
  </div>
</template>

<script>
  import MyNews from './MyNews'
export default {
  components: { MyNews },
    name:"App"
  }
</script>

<style lang="scss" scoped>

</style>