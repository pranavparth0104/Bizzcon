<template>
  <div class="container">
      <img class="img" :src="require(`@/assets/images/home1.jpg`)" alt="">
      <!-- <iframe class="ok" width="100%" height="100%" src="https://www.youtube.com/embed/PYhZfzxCMYA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
/* .container{
    position: relative;
    width: 500px;
    padding-bottom: 56.25%;
    height: 500px;
}
.container .ok{
    position: absolute;
  
    width: 500px;
    height: 500px;
} */
.img{
    width: 50px;
    height: 50px;
}
@media (min-width: 1250px) {
.container img{
    height: 100%;
    width: 100%;
}
}
</style>