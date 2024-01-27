<script setup>
import TheHeader from './components/TheHeader.vue'
import FirstSection from './components/FirstSection.vue'
import SecondSection from './components/SecondSection.vue'
import ThirdSection from './components/ThirdSection.vue'
import FourSection from './components/FourSection.vue'
import FiveSection from './components/FiveSection.vue'
import SixSection from './components/SixSection.vue'
import SevenSection from './components/SevenSection.vue'
</script>

<template>
  <div class="wrapper">
    <TheHeader></TheHeader>
    <main>
      <FirstSection></FirstSection>
      <SecondSection></SecondSection>
      <ThirdSection></ThirdSection>
      <FourSection></FourSection>
      <FiveSection></FiveSection>
      <SixSection></SixSection>
      <SevenSection></SevenSection>
    </main>
  </div>
</template>

<style scoped>
.wrapper {
  width: 100%;
  height: 100%;
}

main {
  width: 100%;
}


</style>
