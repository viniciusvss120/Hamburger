<template>
  <div class="home">
    <Bannes />
    <h2>Monte seu burger:</h2>
    <BurgerForm />
  </div>
</template>

<script>
import Bannes from '../components/Bannes.vue'
import BurgerForm from '../components/BurgerForm.vue'
export default {
  name: 'Home',
  components:{
    Bannes,
    BurgerForm
  }
 
}
</script>

<style scoped>
  h2{
    display: flex;
    justify-content: center;
    margin-bottom: 25px;
    }
</style>
