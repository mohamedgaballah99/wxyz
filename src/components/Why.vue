<template>
  <div class="why">
    <div class="container">
      <div class="row">
        <div class="col-sm-12 col-md-12 col-lg-5" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="200">
          <h1>WHY DEPOT</h1>
          <p>
            Far far away, behind the word mountains, far from the countries
            Vokalia and Consonantia, there live the blind texts.
          </p>
          <ul class="text-left">
            <li><i class="fas fa-check"></i>Cargo express</li>
            <li>
              <i class="fas fa-check"></i>Secure Services
            </li>
            <li><i class="fas fa-check"></i> Secure Warehouseing</li>
            <li><i class="fas fa-check"></i> Cost savings</li>
            <li>
              <i class="fas fa-check"></i> Proven by great companies
              
            </li>
          </ul>
        </div>

        <div class="col-sm-12 col-md-12 col-lg-6" data-aos="fade-left" data-aos-duration="1000" data-aos-delay="200">
          <div class="img">
            <img src="../assets/images/vedio.jpg" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Why",
};
</script>
<style lang="scss" scoped>
.why {
  margin-top: 80px;
  .container {
    .row {
      > div {
        font-family: "Courier New", Courier, monospace;
        margin: 0px 0px 50px 0px;
        h1 {
          color: #007bff;
          font-weight: bold;
        }
        p {
          color: rgb(128, 128, 128);
          line-height: 1.8;
        }
        ul {
          list-style: none;
          li {
            margin: 20px 0px;
            i {
              color: #007bff;
            }
          }
        }
        .img {
          width: 90%;
          img {
            width: 100%;
          }
        }
      }
      div:first-of-type {
        margin: 20px;
      }
    }
  }
}

</style>
