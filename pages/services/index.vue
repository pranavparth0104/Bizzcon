<template>
  <div class="contain">
  <div class="all">
        <h3>Services</h3>
        <div class="view"></div>
    </div>
    <div class="info">
        <h2>Services Offered</h2>
        <p>We offer a wide range of customized, high-quality, research-based talent consulting services. </p>
      </div>

      <div class="con">
        <a href="/services/exe_search">
        <div class="services">
          <img :src="require(`@/assets/service/search.png`)" alt="">
          <div class="data">
            <h4>Executive Search</h4>
          </div>
        </div>
        </a>
        <a href="/services/senior_middle">

        <div class="services">
          <img :src="require(`@/assets/service/senior.png`)" alt="">
          <div class="data">
            <h4>Senior & Middle Level Hiring</h4>
          </div>
        </div>
        </a>
        <a href="/services/rpo">
        <div class="services">
          <img :src="require(`@/assets/service/rpo.png`)" alt="">
          <div class="data">
            <h4>Recruitment Process Outsourcing</h4>
          </div>
        </div>
        </a>
        <a href="/services/global_cov">
        <div class="services">
          <img :src="require(`@/assets/service/coverage.png`)" alt="">
          <div class="data">
            <h4>Global Coverage</h4>
          </div>
        </div>
        </a>
        <a href="/services/global-source">
        <div class="services">
          <img :src="require(`@/assets/service/global_source.png`)" alt="">
          <div class="data">
            <h4>Global Sourcing</h4>
          </div>
        </div>
        </a>
        <a href="/services/inter_capacity">
        <div class="services">
          <img :src="require(`@/assets/service/intern.png`)" alt="">
          <div class="data">
            <h4>International/Cross-Border Capacity</h4>
          </div>
        </div>
        </a>
        <a href="/services/industry">
        <div class="services">
          <img :src="require(`@/assets/service/industry.png`)" alt="">
          <div class="data">
            <h4>Industry Specialization</h4>
          </div>
        </div>
        </a>
        <a href="/services/deep_local">
        <div class="services">
          <img :src="require(`@/assets/service/deep.png`)" alt="">
          <div class="data">
            <h4>Deep Local Knowledge</h4>
          </div>
        </div>
        </a>
        <a href="/services/career_trans">
        <div class="services">
          <img :src="require(`@/assets/service/career.png`)" alt="">
          <div class="data">
            <h4>Career Transition Services</h4>
          </div>
        </div>
        </a>
        <a href="/services/market_intel">
        <div class="services">
          <img :src="require(`@/assets/service/market.png`)" alt="">
          <div class="data">
            <h4>Market Intelligence</h4>
          </div>
        </div>
        </a>
        <a href="/services/recruiter_program">
        <div class="services">
          <img :src="require(`@/assets/icons/recruit.png`)" alt="">
          <div class="data">
            <h4>Recruiter Training Programmes</h4>
          </div>
        </div>
        </a>
        
        

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
.info{
  padding: 20px;
}

.info h2{
  
      color: rgb(252,140,20);

}

.view{
  background: rgb(252,140,20);
  height: 10px;
  width: 80px;
}

.con{
  display: flex;
  padding: 20px;
  margin: 10px;
  justify-content: space-around;
  flex-wrap: wrap;
  flex-direction: row;
}

.services{
  display: flex;
  margin: 10px;
  width: 700px;
  flex-direction: row;
}

.data{
  display: flex;
  
  flex-direction: column;
}
img{
    padding-left: 20px;
    padding-right: 20px ;

}
.data h4{
  color: black;
}

@media screen and (max-width: 600px) {
    .con{
      margin: 0px;
      width: 100%;
    }
    .services{
      width: 100%;
      margin-left: 0;
    }
}
@media screen and (max-width: 700px) {
.con{
  justify-content: initial;
}
}
</style>