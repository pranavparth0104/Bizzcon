<template>
  <!-- Footer -->
  <footer class="footer">
  <mdb-footer style="backgroundColor: #000000" color="stylish-color-dark" class="font-small pt-4 mt-4">
    <mdb-container  class="text-center text-md-left">
      <mdb-row class="text-center text-md-left mt-3 pb-3">
        <mdb-col md="3" lg="3" xl="3" class="mx-auto mt-3">
          <h6 style="color: #ffff" class="text-uppercase mb-4 font-weight-bold">Bizzcon</h6>
          <p style="color: #ffff">Bizzcon solutions aims to serve as trusted advisers to our valued clients, partnering with them in making their most important decisions.</p>
        </mdb-col>
        <hr class="w-100 clearfix d-md-none" />
        <mdb-col md="2" lg="2" xl="2" class="mx-auto mt-3">
          <h6 style="color: #ffff" class="text-uppercase mb-4 font-weight-bold">BIZZCON</h6>
          <a href="/about_us/whybizzcon"><p><a  style="color: #ffff" href="/about_us/whybizzcon">ABOUT US</a></p></a>
          <a href="/jobs/post"><p><a style="color: #ffff" href="/jobs/post">JOBS</a></p></a>
          <a href="/industries"><p><a style="color: #ffff" href="/industries">INDUSTRY</a></p></a>
        </mdb-col>
        <hr class="w-100 clearfix d-md-none" />
        <mdb-col md="3" lg="2" xl="2" class="mx-auto mt-3">
          <h6 style="color: #ffff" class="text-uppercase mb-4 font-weight-bold">About</h6>
          <a href="/about_us/leaders"><p><a style="color: #ffff" href="/about_us/leaders">LEADERS</a></p></a>
          <a href="/about_us/life"><p><a style="color: #ffff" href="/services">SERVICES</a></p></a>
          <a href="/about_us/board"><p><a style="color: #ffff" href="/insights">INSIGHTS</a></p></a>
        </mdb-col>
        <hr class="w-100 clearfix d-md-none" />
        <mdb-col md="4" lg="3" xl="3" class="mx-auto mt-3">
          <h6 style="color: #ffff" class="text-uppercase mb-4 font-weight-bold">Contact Us</h6>
          <p style="color: #ffff"><i class="fas fa-home mr-3"></i> BENGALURU</p>
          <p style="color: #ffff"><i class="fas fa-envelope mr-3"></i>BIzzcon Solutions Pvt. Ltd.</p>
                    <p style="color: #ffff"><i class="fas fa-envelope mr-3"></i>OMBR Layout, Kalyan Nagar </p>
<p style="color: #ffff"><i class="fas fa-envelope mr-3"></i>Bengaluru 560043
Karnataka</p>

          <!-- <p style="color: #ffff"><i class="fas fa-phone mr-3"></i> +91 11 4934 3900</p>
          <p style="color: #ffff"><i class="fas fa-print mr-3"></i> +91 11 4934 3900</p> -->
        </mdb-col>
      </mdb-row>
      <hr />
      <mdb-row class="d-flex align-items-center">
        <mdb-col md="8" lg="8">
          <p style="color: #ffff" class="text-center text-md-left grey-text">&copy; 2021 Copyright: Business Solutions</p>
        </mdb-col>
        <mdb-col md="4" lg="4" class="ml-lg-0">
          <div class="text-center text-md-right">
            <ul class="list-unstyled list-inline">
              <li class="list-inline-item"><a class="btn-floating btn-sm rgba-white-slight mx-1"><i class="fab fa-facebook"></i></a></li>
              <li class="list-inline-item"><a class="btn-floating btn-sm rgba-white-slight mx-1"><i class="fab fa-twitter"></i></a></li>
              <li class="list-inline-item"><a class="btn-floating btn-sm rgba-white-slight mx-1"><i class="fab fa-google-plus"></i></a></li>
              <li class="list-inline-item"><a class="btn-floating btn-sm rgba-white-slight mx-1"><i class="fab fa-linkedin-in"></i></a></li>
            </ul>
          </div>
        </mdb-col>
      </mdb-row>
    </mdb-container>
  </mdb-footer>
  </footer>
  <!-- Footer -->
</template>

<script>
  import { mdbFooter, mdbContainer, mdbRow, mdbCol } from 'mdbvue';
  export default {
    name: 'FooterPage',
    components: {
      mdbFooter,
      mdbContainer,
      mdbRow,
      mdbCol
    }
  }
</script>

<style scoped>
.footer{
  
  top: 0px; 
}
</style>