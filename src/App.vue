<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <router-view></router-view>
  </div>
</template>

<script>
  import MHeader from 'components/m-header/m-header'
  import Tab from 'components/tab/tab'
  export default {

    components: {
      MHeader,
      Tab
    }
  }
</script type="text/ecmascript-6">

<style scoped lang="stylus" rel="stylesheet/stylus">
</style>
