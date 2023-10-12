<template>
  <HeaderCabecalho/>
  <PrimeiraSection/>
  <SegundaSection/>

</template>

<script>
import HeaderCabecalho from './components/HeaderCabecalho.vue'
import PrimeiraSection from './components/PrimeiraSection.vue'
import SegundaSection from './components/SegundaSection.vue'



export default {
  name: 'App',
  components: {
    HeaderCabecalho,
    PrimeiraSection,
    SegundaSection

  }
}
</script>

<style>
body{
  font-family: poppins, Helvetica, Arial, sans-serif;
  background-color: #F1F2FB;
}
</style>
