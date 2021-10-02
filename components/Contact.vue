<template>
  <div class="contact">
      <br><br>
      <div class="contact_us">
        <div class="add">
         <div>
          <h4>Corporate Office :</h4>
          <br>
          <br>
          <h4>NOIDA</h4>
          <h5>
            BIzzcon Solutions Pvt. Ltd.</h5>
            <h5>
SD-114, Sector 45 , Noida Gautam Budh Nagar , UP - 201301
          </h5>
          <br><br>
          <h4>
            BENGALURU
          </h4>
          <h5>BIzzcon Solutions Pvt. Ltd.</h5>
          <h5>
            OMBR Layout 
          </h5>
          <h5>
            Kalyan Nagar, Bengaluru 560043
Karnataka
          </h5>
          <br><br>
          <!-- <h6>1st Floor, Eros Corporate Tower</h6>
          <h6>Nehru Place</h6>
          <h6>New Delhi 110 019</h6>
          <br>

          <h6>T: +91 11 4934 3900</h6>
          <h6>E: info@abcconsultants.in</h6> -->
        </div>
        
        <br>
        <br>
        
        
      </div>
      <div class="map">
        <Map />
      </div>
      </div>
      
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.contact_us{
  
  display: flex;
  flex-direction: row;
}
.add{
  text-align: center;
  padding: 15px;
  display: flex;
  width: 100%;
  justify-content: space-evenly;
  flex-direction: row;
}
.contact{
   text-align: center;
  padding: 10px;

  background: white;
  margin-bottom: 0px;
}
.map{
  width: 100%;
}
.add h4{
}
.contact h2{
  font-size: 40px;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

@media screen and (max-width: 700px) {
  
.contact_us{
  flex-direction: column;
}
  
}
</style>