<template>
  <div>
    <h1>这是测试添加新功能组件</h1>
    <!-- name的作用就是缓存下来页面里面的数据，切换到b页面之后再切换回aa页面的时候input标签写的临时内容不会丢失 -->
    <input type="text" />
  </div>
</template>

<script>
export default {
  name: "AA"
};
</script>

<style>
</style>
