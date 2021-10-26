<template>
    <div id="main-banner">
        <h1>MAKE YOUR BURGER</h1>
    </div>
</template>

<script>
export default {
 name: 'Banner',
 data(){
     return{

     }
 }


}
</script>

<style scoped>
     #main-banner {
    background-image: url('/img/burger.jpg');
    background-position: 0 -350px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }
  #main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
  }
</style>