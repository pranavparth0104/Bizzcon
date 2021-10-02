<template>
  <div class="contain">
    <div class="all">
          <h2>Why Bizzcon</h2>
          <p>“Bizzcon Solutions (BCS) where “Bizzcon” stands for Business consulting aims to serve as trusted advisers to our valued clients, partnering with them in making their most important decisions – planning, recruiting, selecting, and retaining superior talent. We are more than just head-hunters; we pride ourselves on the close involvement of our consultants in each search mandate.</p>
          <div class="view"></div>
    </div>
    <div class="info">
      <p>Designed to support the complexity of the regional Industry and Services market, with organisations becoming increasingly diverse and globally competitive, our mission is to deliver valuable service levels, efficient external resources and highly-qualified professionals. BCS supports Talent Acquisition activities across the region for clients who seek to hire the best available individuals, striving to ultimately improve their company performance.</p>
      <br>
      <p>
        As an HR consulting firm, we have highly experienced staffing teams who lay high emphasis on candidate quality and are experienced professionals themselves in each of the Industry and Services sectors they support.
      </p>
      <br>
      <p>
        BCS deploys hiring capability suiting global search‐based solutions across worldwide. We are a recruitment agency that provides sharp information and assistance in making the most cost‐effective decision, achieving the hire of the right candidate.
      </p>
      <br>
      <p>
        We take pride in working with clients as partners to attain measurable results and performance improvements through the provision of reliable and flexible workforce solutions.
      </p>
      <div class="cards">
      <div class="cards">
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <h4>DEDICATED RECRUITER</h4>
            </div>
            <div class="flip-card-back">
              <h4>Are you in growth mode and need recruiting support?</h4>
             </div>
          </div>
        </div>
      </div>
      <div class="cards">
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <h4>MAKING A STRATEGIC HIRE</h4>
            </div>
            <div class="flip-card-back">
              <h4>Are you seeking a trusted partner to find, attract, and hire a senior leader?</h4>

            </div>
          </div>
        </div>
      </div>
      <div class="cards">
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <h4>TALENT ACQUISITION CONSULTING
</h4>
            </div>
            <div class="flip-card-back">
              <h4>Are your recruitment efforts falling short and you want support?</h4>

            </div>
          </div>
        </div>
      </div>
      <div class="cards">
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <h4>QUALITY</h4>
            </div>
            <div class="flip-card-back">
              <h4>Are you looking for quality resource for your requirement?</h4>

            </div>
          </div>
        </div>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>

.contain{
  width: 100%;
}
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
}
.info h2{
      color: rgb(252,140,20);

}
.flip-card {
  background-color: transparent;
  width: 300px;
  height: 200px;
  border: 1px solid #f1f1f1;
  perspective: 1000px; /* Remove this if you don't want the 3D effect */
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.cards{
  display: flex;
  padding: 20px;
  justify-content: space-around;
  flex-wrap: wrap;
}

.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden; /* Safari */
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: rgba(255,181,17,255);
  color: white;
  padding: 30px;
}

.flip-card-back {
  background-color: rgba(255,181,17,255);
  color: white;
  padding: 10px;
  text-align: left;
  transform: rotateY(180deg);
}

</style>

