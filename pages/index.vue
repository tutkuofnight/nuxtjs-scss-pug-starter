<script>
import {mapState} from 'vuex'
export default {
  name: 'IndexPage',
  computed: {
    ...mapState(['text'])
  }
}
</script>

<template lang="pug">
#app
  h1 {{text}}
</template>

<style lang="scss">

</style>