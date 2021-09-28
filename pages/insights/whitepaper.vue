<template>
  <div class="contain">
  <div class="all">
        <h3>White Paper</h3>
        <p>Bizzcon is the pioneer of organised recruitment in India. Our roots in management consulting enable us to bring a unique approach to recruitment.</p>
        <div class="view"></div>
      </div>
      <div class="info">
       <img :src="require(`@/assets/ai.jpg`)" alt="">
       <div class="inf">
            <h2>Artificial Intelligence in Recruitment</h2>
            <p>In the wake of rapid changes in business needs, workforce demographics, technology, lifestyle, and information technologies, the challenges for the Talent Acquisition function have grown manifold. To change constantly yet remain predictable, being agile yet showing long term benefits, customize yet standardized – these are some of the demands that are placed in front of the TA function. Balancing all these factors will prove to be a challenge for recruitment professionals. Artificial intelligence (AI) makes it possible for machines to learn from experience, adjust to new inputs and perform human-like tasks. Most AI examples that you hear about today – from chess-playing computers to self-driving cars – rely heavily on deep learning and natural language processing. Using these technologies, computers can be trained to accomplish specific tasks by processing large amounts of data and recognizing patterns in the data.</p>
       </div>
      </div>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.all{
  background: url(https://images.unsplash.com/photo-1436262513933-a0b06755c784?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=871&q=80);
  text-align: left;
  color: white;
  padding: 30px;
  width: 100%;
}

.all h2{
  font-size: 40px;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

.all p{
    font-size: 20px;

}

.view{
  background: rgb(252,140,20);
  height: 10px;
  width: 80px;
}

.info{
  padding: 20px;
  display: flex;
}
.info img{
    width: 50%;
}

.inf{
    padding: 20px;

}
.inf h2{
    color: rgb(252,140,20);
}
.inf h2{
    font-size: 30px;
}
.inf p{
    font-size: 23px;
}

@media screen and (max-width: 1000px) {
  .info{
      flex-direction: column;
  }
  .info img{
      width: 100%;
  }
}
</style>