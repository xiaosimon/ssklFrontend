<script>
export default {
  methods: {
    goToAbout() {
      this.$router.push('/about')
    },
  },
}
</script>

<template>
  <!-- <h2>HomeView</h2> -->
  <!-- <button @click="goToAbout">Go to About</button> -->
   <div class="mdmain">
    md render
   </div>
</template>
<style scoped>
.mdmain{
    width: 100%;
    height:calc( 100% - 100px );
}
</style>