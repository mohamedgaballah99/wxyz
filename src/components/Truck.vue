<template>
  <div class="track">
    <div class="container">
      <div class="row">
        <div class="col-sm-12 col-md-4"  data-aos="fade-right" data-aos-duration="1000" data-aos-delay="100">
          <div class="img">
            <img src="../assets/images/1.jpg" />
          </div>
          <div class="info">
            <h3>Truck Insurance</h3>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
          </div>
        </div>

        <div class="col-sm-12 col-md-4"  data-aos="fade-down" data-aos-duration="800" data-aos-delay="100">
          <div class="img">
            <img src="../assets/images/2.jpg" />
          </div>
          <div class="info">
            <h3>Plane Transportation</h3>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
          </div>
        </div>

        <div class="col-sm-12 col-md-4"  data-aos="fade-left" data-aos-duration="800" data-aos-delay="100">
          <div class="img">
            <img src="../assets/images/header.jpg" class="ship" />
          </div>
          <div class="info">
            <h3>Sea & Ear Freight</h3>
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
  name: "Truck",
};
</script>
<style lang="scss" scoped>
.track {
  margin-top: 100px;
  .container {
    .row {
      > div {
        text-align: center;
        margin-bottom: 30px;
        .img {
          width: 100%;
          img {
            width: 100%;
            cursor: pointer;
            transition: 0.7s all;
            overflow: hidden;
            &:hover {
              transform: scale(1.05);
            }
          }
        }
        .info {
           font-family: 'Courier New', Courier, monospace;
          h3 {
            margin: 15px 0px;
            color: #007bff;
            cursor: pointer;
            font-weight: bold;
          }
          p {
            color: gray;
            line-height: 1, 8;
          }
        }
        .ship {
          height: 220px;
        }
      }
    }
  }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .ship {
    height: 133px !important;
  }
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .ship {
    height: 183px !important;
  }
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
  .ship {
    height: 220px !important;
  }
}
</style>
