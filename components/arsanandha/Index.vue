<template>
  <div class="centerLogo"  @mouseover="showText = true" @mouseleave="showText = false">
    <div>
      <img :src="logo" alt="ARSANANDHA.xyz Logo"/>
    </div>
    <p v-if="showText">Coming soon ... (arsanandha.xyz)</p>
  </div>
</template>

<script lang="ts">
export default {
  name: "Index",
  data: function () {
    return {
      logo: require("../logo/arsanandha.xyz-v2-01.png"),
      showText: false
    }
  }
}
</script>

<style scoped lang="css">
.centerLogo {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
</style>
