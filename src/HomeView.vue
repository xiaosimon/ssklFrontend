<script setup>
import MdCmp from "./components/MdCmp.vue";

// export default {
//   methods: {
//     goToAbout() {
//       this.$router.push('/about')
//     },
//   },
// }
</script>

<template>
  <!-- <h2>HomeView</h2> -->
  <!-- <button @click="goToAbout">Go to About</button> -->
  <div class="main">
    <MdCmp></MdCmp>
    <div class="footArea">
      <textarea name="ask" id="ask"></textarea>
      <button id="btn">submit</button>
    </div>
  </div>
</template>
<style scoped>
.main {
  width: 100%;
  height: 100%;
  padding: 20px;
}
.footArea {
  width: 100%;
  height: 100px;
  display: flex;
}
#ask {
  width: calc(100% - 100px);
  height: 100%;
}
#btn{
    cursor: pointer;
    width: 100px;
}
</style>
