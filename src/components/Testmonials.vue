<template>
  <div class="test">
    <div class="container" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="200">
      <h1>Happy Clients</h1>
       <VueSlickCarousel :arrows="true" :dots="true" :autoplay="true" :nav="false">
          
        <div>
          <p>
            “Even the all-powerful Pointing has no control about the blind texts
            it is an almost unorthographic life One day however a small line of
            blind text by the name of Lorem Ipsum decided to leave for the far
            World of Grammar.”
          </p>
          <div class="img">
            <img src="../assets/images/person1.jpg" />
          </div>
        </div>

        <div>
          <p>
            “A small river named Duden flows by their place and supplies it with
            the necessary regelialia. It is a paradisematic country, in which
            roasted parts of sentences fly into your mouth.”
          </p>
          <div class="img">
            <img src="../assets/images/person2.jpg" />
          </div>
        </div>

        <div>
          <p>
            “Far far away, behind the word mountains, far from the countries
            Vokalia and Consonantia, there live the blind texts. Separated they
            live in Bookmarksgrove right at the coast of the Semantics, a large
            language ocean.”
          </p>
          <div class="img">
            <img src="../assets/images/person3.jpg" />
          </div>
        </div>

        <div>
          <p>
            “The Big Oxmox advised her not to do so, because there were
            thousands of bad Commas, wild Question Marks and devious Semikoli,
            but the Little Blind Text didn’t listen. She packed her seven
            versalia, put her initial into the belt and made herself on the
            way.”
          </p>
          <div class="img">
            <img src="../assets/images/person1.jpg" />
          </div>
        </div>

        <div>
          <p>
            “A small river named Duden flows by their place and supplies it with
            the necessary regelialia. It is a paradisematic country, in which
            roasted parts of sentences fly into your mouth.”
          </p>
          <div class="img">
            <img src="../assets/images/person2.jpg" />
          </div>
        </div>

        <div>
          <p>
            “Even the all-powerful Pointing has no control about the blind texts
            it is an almost unorthographic life One day however a small line of
            blind text by the name of Lorem Ipsum decided to leave for the far
            World of Grammar.”
          </p>
          <div class="img">
            <img src="../assets/images/person3.jpg" />
          </div>
        </div>
      </VueSlickCarousel>

      
    </div>
  </div>
</template>
<script>
import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
  name: "test",
  components: {VueSlickCarousel },
};
</script>
<style lang="scss" scoped>
.test {
  margin-top: 40px;
  margin-bottom: 80px;
  .container {
    font-family: "Courier New", Courier, monospace;

    h1 {
      color: #007bff;
      font-weight: bold;
      text-align: center;
      margin-bottom: 60px;
    }
    > div {
      p {
        font-weight: bold;
        line-height: 2;
        padding: 30px;
      }
      .img {
        width: 100px;
        margin: auto;
        img {
          width: 100%;
          border-radius: 50%;
        }
      }
       
    }

  }
  
}
</style>
