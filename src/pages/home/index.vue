<template>
  <div class="home__container">
    <!-- <div><i-button type="primary" bind:click="handleClick">这是一个按钮</i-button></div> -->
    <div></div>
  </div>
</template>

<script>
export default {
  data () {
    return {}
  },

  components: {},

  methods: {
    clickHandle (ev) {
      console.log('clickHandle:', ev)
    }
  },
}
</script>

<style scoped>
.home__container {

}
</style>
