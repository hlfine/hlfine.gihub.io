<!--
 * @Description: 
 * @Autor: hanl
 * @Date: 2021-01-14 14:13:36
 * @LastEditors: hanl
 * @LastEditTime: 2021-01-14 14:16:04
-->

<template>
  <div>{{ msg }}</div>
</template>

<script>
export default {
  name: 'NewComponent',
  props: {
    msg: {
      type: String,
      default: 'NewComponent'
    }
  },
  data() {
    return {};
  },
}
</script>

<style lang='scss' scoped>
</style>