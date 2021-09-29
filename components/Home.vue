<template>
<div>
  <div class="intro">
    <You />
    <div class="intro_cont">
      <div class="about_us">
        <h3>About Us</h3>
        <p>Business consulting (Bizzcon) aims to serve as trusted advisers to our valued clients, partnering with them in making their most important decisions.</p>
        <a href="/about_us/whybizzcon"><button href>LEARN MORE</button></a>
      </div>
      <div class="services">
        <h3>Services</h3>
        <p>We provide a range of talent acquisition services by leveraging our domain knowledge.</p>
        <a href="/services"><button href>LEARN MORE</button></a>
      </div>
    </div>
  </div>
  <div class="home_2">
    <h3>Creating Impact</h3>
    <div class="impact">
      <div class="one">
        <h1>50+</h1>
        <p>Years of market leadership</p>
      </div>
      <div class="one">
        <h1>165k</h1>
        <p>Careers made till date</p>
      </div>
      <div class="one">
        <h1>465+</h1>
        <p>Consultants</p>
      </div>
      <div class="one">
        <h1>25</h1>
        <p>Industries Covered</p>
      </div>
    </div>

  </div>  
    <div class="image">
      <img :src="require(`@/assets/img.jpg`)" alt="">
      <div class="ind">
        <h2>Industry Practices</h2>
        <p>In order to provide clients with specialised recruiting solutions, Bizzcon has developed expertise in the following industry segments:</p>
        <div class="slider">
          <img class="indu" style="width:20%" :src="require(`@/assets/service/industry.png`)" alt="">
        </div>
        <br>
        <br>
        <a href="/industries"><button href="/industries">LEARN MORE</button></a>
        <br>
        
      </div>
    </div>
    <!-- <div class="testimonials">
      <h2>Client Testimonials</h2>
      <br><br>
      <div class="slider">
          <Tslider />
        </div>
        <br>
        <br>
    </div> -->
    <div class="contact">
      <h2>Contact Us</h2>
      <br><br>
      <div class="contact_us">
        <div class="add">
        <div>
          <h4>Corporate Office :</h4>
          <br>
          <br>
          <h4>NEW DELHI</h4>
          <br><br>
          <h4>
            BENGALURU
          </h4>
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
        <!-- <div>
         <h4>Main Office</h4>
         <br>
        <h5>Bengaluru</h5>
        <h6>1st Floor, Eros Corporate Tower</h6>
        <h6>Benargatta</h6>
        <h6>Bengaluru</h6> 
        <br>
        <h6>T: +91 11 4934 3900</h6>
          <h6>E: info@abcconsultants.in</h6>
        </div> -->
        
      </div>
      <div class="map">
        <Map />
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
.intro{
  display: flex;
  flex-direction: row;
}

.about_us{
  background: rgba(255,181,17,255);
  text-align: center;
  color: black;
  padding: 20px;
}
.about_us p{
      font-size: 17px;

}

.about_us button{
  border: none;
  padding: 10px;
  color: white;
  border-radius: 5px;

  background: black;
}
.indu{
  width: 20px;
}
.image button{
  border: none;
  padding: 10px;
  color: white;
   border-radius: 5px;

  background: black;
}

.image h2{
  font-size: 40px;
}

.intro_cont{
  display: flex;
  flex-direction: column;
}

.services{
  background: rgb(252,140,20);
  text-align: center;
  color: black;
  padding: 20px;
}

.services button{
  border: none;
  padding: 10px;
  color: white;
  background: black;
  border-radius: 5px;

}

.services p{
        font-size: 17px;

}

.home_2{
  background: rgba(255,181,17,255);
  text-align: center;
  color: white;
  padding: 20px;
 
}

.home_2 h3{
  font-size: 40px;
}
.image{
  display: flex;
  flex-direction: row;
}
.impact{
  margin-top: 20px;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}

.ind{
  text-align: center;
  padding: 10px;

  background: rgb(252,140,20);
}

.contact_us{
  
  display: flex;
  flex-direction: row;
}
.contact{
   text-align: center;
  padding: 10px;

  background: rgba(255,181,17,255);
  margin-bottom: 0px;
}


.add{
  text-align: center;
  padding: 15px;
  display: flex;
  width: 100%;
  justify-content: space-evenly;
  flex-direction: row;
}
.map{
  width: 100%;
}
.add h4{
  font-style: oblique;
}
.contact h2{
  font-size: 45px;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.testimonials{
  text-align: center;
  padding: 10px;

  background: rgba(255,181,17,255);

}

.testimonials button{
  border: none;
  padding: 10px;
  color: white;
  background: black;
  border-radius: 5px;

}

.testimonials h2{
  font-style: italic;
  font-size: 40px;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.testimonials p{
        font-size: 17px;

}
.ind h2{
  font-style: italic;
  font-size: 40px ;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;


}


.ind p{
  font-size: 25px;
}
.one{
  display: flex;
  flex-direction: column;
  padding: 10px;
}
.image img{
  width: 50%;
}

.one h1{
  font-style: italic;
  font-size: 60px ;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.home_2 h3{
   font-family: Georgia, 'Times New Roman', Times, serif;
   font-style: italic;
}


@media screen and (max-width: 700px) {
  .intro{
    flex-direction: column;
  }
  .impact{
  flex-direction: column;
}

.add{
flex-direction: row;

}
.contact_us{
  flex-direction: column;
}
  
}

@media screen and (max-width: 900px) {
.image{
    flex-direction: column;
  }
  .image img{
    width: 100%;
  }
}
@media screen and (max-width: 1000px) {
.ind p{
  font-size: 15px;
}
}
</style>