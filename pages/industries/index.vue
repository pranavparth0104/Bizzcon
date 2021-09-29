<template>
  <div class="contain">
  <div class="all">
        <h3>Industrial Practices</h3>
        <div class="view"></div>
      </div>
      <div class="info">
        <p>Bizzcon has developed expertise in the following industry segments:</p>
      </div>
      <div class="ind">
        <a href="/industries/automotive">
        <div class="data">
          
          <h4>Automotive Industry</h4>
          
        </div>
        </a>
        <a href="/industries/aerospace">

        <div class="data">
          <h4>Aerospace and Defence</h4>
        </div>  
        </a>
        <a href="/industries/banking">  
        <div class="data">
          <h4>Banking</h4>
        </div> 
        </a>
        <a href="/industries/corporate_banking">   
        <div class="data">
          <h4>Corporate & Investment Banking</h4>
        </div> 
        </a>
        <a href="/industries/consumer">
        <div class="data">
          <h4>Consumer Products</h4>
        </div>
        </a>
        <a href="/industries/finance">
        <div class="data">
          <h4>Financial Service</h4>
        </div>
        </a>
        <a href="/industries/fmcg">
        <div class="data">
          <h4>FMCG</h4>
        </div>
        </a>
        <a href="/industries/gov_sec">
        <div class="data">
          <h4>Government (Public Sector)</h4>
        </div>
        </a>
        <a href="/industries/health">
        <div class="data">
          <h4>Healthcare</h4>
        </div>
        </a>
        <a href="/industries/high_tech">
        <div class="data">
          <h4>High Tech & Semiconductors</h4>
        </div>
        </a>
        <a href="/industries/infrastructure">
        <div class="data">
          <h4>Infrastructure</h4>
        </div>
        </a>
        <a href="/industries/insurance">
        <div class="data">
          <h4>Insurance</h4>
        </div>
        </a>
        <a href="/industries/pharma">
        <div class="data">
          <h4>Lifesciences & Pharma</h4>
        </div>
        </a>
        <a href="/industries/media">
        <div class="data">
          <h4>Media & Entertainment</h4>
        </div>
        </a>
        <a href="/industries/oil">
        <div class="data">
          <h4>Oil & Gas</h4>
       </div>
       </a>
       <a href="/industries/outsourcing">
        <div class="data">
          <h4>Outsourcing and Offshoring</h4>
        </div> 
        </a>
        <a href="/industries/pro_service">
        <div class="data">
          <h4>Professional Services</h4>
        </div> 
        </a>
        <a href="/industries/software">
         <div class="data">
          <h4>Software & IT platforms</h4>
        </div> 
        </a>
        <a href="/industries/services">
        <div class="data">
          <h4>Services</h4>
        </div>
        </a> 
        <a href="/industries/tech">
        <div class="data">
          <h4>Technology</h4>
        </div>
        </a> 
        <a href="/industries/tele">
        <div class="data">
          <h4>Telecommunications</h4>
        </div> 
        </a>
        <a href="/industries/telecom">
        <div class="data">
          <h4>Telecom</h4>
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

.view{
  background: rgb(252,140,20);
  height: 10px;
  width: 80px;
}

.info{
  padding: 20px;
}

.data{
  padding: 20px;
  width: 500px;
  margin: 10px;

  border-bottom: 1px solid black;
}

.ind{
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  color: black;
  justify-content: space-around;
}

.ind h4{
  color: black;
  
}

@media screen and (max-width: 900px) {
    .ind{
        display: flex;
        flex-direction: column;
    }
    .data{
      width: 100%;
    }
}

</style>