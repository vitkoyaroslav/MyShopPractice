<template>
<div>
  <MainHeader/>
  <nuxt/>
</div>
</template>

<style scoped lang="sass">
  ul
    padding: 0
    margin: 10px 0 0
    list-style: none
    display: flex
    justify-content: space-around
</style>
<script>
  import MainHeader from "../components/MainHeader";
  export default {
    components: { MainHeader }
  }
</script>