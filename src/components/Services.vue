<template>
  <div class="services">
    <div class="container">
      <div class="info"  data-aos="fade-down" data-aos-duration="800" data-aos-delay="100">
        <h1>Services</h1>
        <p>
          Far far away, behind the word mountains, far from the countries
          Vokalia and Consonantia, <br>there live the blind texts.
        </p>
      </div>

      <div class="row">

        <div class="col-sm-12 col-md-6 col-lg-4"  data-aos="fade-right" data-aos-duration="1000" data-aos-delay="200">
            <span><i class="fas fa-ship"></i></span>
          <div class="info">
            <h4>Truck Insurance</h4>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
          </div>
        </div>

        <div class="col-sm-12 col-md-6 col-lg-4" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200">
            <span><i class="fas fa-plane"></i></span>
          <div class="info">
            <h4>Plane Transportation</h4>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
          </div>
        </div>

        <div class="col-sm-12 col-md-6 col-lg-4" data-aos="fade-left" data-aos-duration="1000" data-aos-delay="200">
            <span><i class="fas fa-box"></i></span>
          <div class="info">
            <h4>Sea & Ear Freight</h4>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
          </div>
        </div>

        <div class="col-sm-12 col-md-6 col-lg-4" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="200">
            <span><i class="fas fa-truck"></i></span>
          <div class="info">
            <h4>Sea & Ear Freight</h4>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
          </div>
        </div>

        <div class="col-sm-12 col-md-6 col-lg-4" data-aos="fade-down" data-aos-duration="1000" data-aos-delay="200">
            <span><i class="fas fa-warehouse"></i></span>
          <div class="info">
            <h4>Sea & Ear Freight</h4>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
          </div>
        </div>

        <div class="col-sm-12 col-md-6 col-lg-4" data-aos="fade-left" data-aos-duration="1000" data-aos-delay="200">
            <span><i class="fas fa-truck-loading"></i></span>
          <div class="info">
            <h4>Sea & Ear Freight</h4>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Services",
};
</script>
<style lang="scss" scoped>
.services {
    margin-top: 100px;
    background-color: rgba(189, 189, 189, 0.397);
    padding: 100px 0px 40px 0px;
  .container {
      >.info{
          text-align: center;
          h1{
              color:#007bff;
              margin: 20px 0px;
               font-family: 'Courier New', Courier, monospace;
               font-weight: bold;
          }
          p{
              color: gray;
              line-height: 1.8;
               font-family: 'Courier New', Courier, monospace;
          }
      }
      .row{
          .col-sm-12{
              padding-bottom: 100px;
              transition: 0.5s all;
              padding: 40px;
              &:hover{
                  background-color: white;
              }
              span{
                  i{
                      
                  display: block;
                  text-align: center;
                  color: #007bff;
                  font-size: 42px;
                  }
              }
              .info{
                  text-align: center;
                  h4{
                      margin: 20px 0px;
                      color: #0d0e0f;
                       font-family: 'Courier New', Courier, monospace;
                       font-weight: bold;
                  }
                  p{
                      // line-height: 1.8;
                      color: gray;
                       font-family: 'Courier New', Courier, monospace;
                  }
              }
          }
      }
  }
}
</style>
