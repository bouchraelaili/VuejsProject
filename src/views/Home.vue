<template>
  <div class="home">
    <ParcourList title="Formation"/>
    <ParcourInput/>
    <ParcourList title="Experience"/>
    <ParcourInput/>
    <ParcourList title="technologie"/>
    <ParcourInput/>
  </div>
</template>

<script>
import ParcourList from '@/components/ParcourList'
import ParcourInput from '../components/ParcourInput.vue'

export default {
  name: "Home",
  components: {
    ParcourList,
    ParcourInput,
  }
}
</script>