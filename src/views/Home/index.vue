<script setup>
import HomeBanner from "./components/HomeBanner.vue"

</script>
<template>
  
    <HomeBanner></HomeBanner>
    
</template>


<style scoped>

.HomeHeader {
  position: absolute;
  top: 0;
  right: 200px;
  width: 100%;
  z-index: 2;
  background-color: rgba(255, 255, 255, 0.5); /* 设置透明度为 0.5 */
}
</style>