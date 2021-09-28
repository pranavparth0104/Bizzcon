<template>
  <div class="container">
    <VueSlickCarousel :arrows="true" :dots="true" class="slider">
      <div class="con">
        <h2>Health Care</h2>
        <img :src="require(`@/assets/icons/health.png`)" alt="">
      </div>
      <div class="con">
        <h2>Banking</h2>
        <img :src="require(`@/assets/icons/bank.png`)" alt="">
      </div>
      <div class="con">
        <h2>Financial Services:</h2>
        <img :src="require(`@/assets/icons/finance.png`)" alt="">
      </div>
      <div class="con">
        <h2>Media and Entertainment</h2>
        <img :src="require(`@/assets/icons/media.png`)" alt="">
      </div>
      <div class="con">
        <h2>Automotive Industry</h2>
        <img :src="require(`@/assets/icons/auto.png`)" alt="">
      </div>
      <div class="con">
        <h2>Insurance</h2>
        <img :src="require(`@/assets/icons/insurance.png`)" alt="">
      </div>
      <div class="con">
        <h2>Consumer Products</h2>
        <img :src="require(`@/assets/icons/consume.png`)" alt="">
      </div>
      <div class="con">
        <h2>Infrastructure</h2>
        <img :src="require(`@/assets/icons/infra.png`)" alt="">
      </div>
      <div class="con">
        <h2>Life sciences & Pharma</h2>
        <img :src="require(`@/assets/icons/pharma.png`)" alt="">
      </div>
      
      
    </VueSlickCarousel>
  </div>
</template>
 
<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
 
  export default {
    name: 'MyComponent',
    components: { VueSlickCarousel },
  }
</script> 

<style scoped>
.container{
    display: flex;
    justify-content: space-around;
}
.slider{
    width: 300px;
}
h2{
    font-size: 40px;
}

.con{
  text-align: center;
}

.con img{
  margin: auto;
}
@media screen and (max-width: 1000px) {
  h2{
    font-size: 30px;
}
}
</style>