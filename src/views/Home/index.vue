<script setup>
import HomeHeader from "../Header/index.vue"
import HomeFixed from "../Fixde/index.vue"
import HomeBody from "../Body/index.vue"
import HomeFooter from "../Footer/index.vue"
import Float from "../Float/index.vue"
import { useWindowScroll } from '@vueuse/core'
import {ref, computed} from 'vue'

const { y } = useWindowScroll()
const showHomeFixed= ref(false) 
showHomeFixed.value = computed(() => {
      return y.value > 125 ? true:false
})
</script>
<template>
  
    <HomeHeader></HomeHeader>
    <Transition name="slide-fade">
      <HomeFixed class="HomeFixed" v-if="showHomeFixed.value" ></HomeFixed>
    </Transition>
    <HomeBody></HomeBody>
    <HomeFooter></HomeFooter>
    <Float></Float>
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
.HomeFixed{
  position: fixed;
  top:0;
}
.slide-fade-enter-active {
  transition: all 0.3s ease-out;
}

.slide-fade-leave-active {
  transition: all 0.5s cubic-bezier(1, 0.5, 0.8, 1);
}

.slide-fade-enter-from,
.slide-fade-leave-to {
  transform: translateY(5px);
  opacity: 0;
}
</style>