<template lang="jade">
#vfooter
  p © 2017 {{$store.state.config.author}}
</template>

<script>
export default {
  name: 'vfooter'
}
</script>


<style lang="stylus" scoped>
#vfooter
  text-align center
  padding 10px 0px
</style>
