<docs>
  # 标题2
    这是标题内容，[仓库地址](https://github.com/yugasun/You-May-Not-Know-Vuejs)
  ## 子标题2
    这是子标题内容
</docs>
<template>
  <h1>{{ msg }}</h1>
</template>
<script>
export default {
  name: 'hello2',
  data () {
    return {
      msg: 'Hello Vue.js 单文件组件~'
    }
  }
}
</script>
<style lang="scss" scoped>
h1 {
  color: $red;
}
</style>


