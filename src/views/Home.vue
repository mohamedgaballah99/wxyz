<template>
  <div class="home">
    <div class="top">
      <span><i class="fas fa-chevron-up"></i></span>
    </div>
    <Header></Header>
    <Truck></Truck>
    <Services id="Services"></Services>
    <About id="AboutUs"></About>
    <Why id="WhyUs"></Why>
    <Testmonials id="Testimonials"></Testmonials>
    <Blog id="Blog"></Blog>
    <Contact id="Contact"></Contact>
    <Social></Social>
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Truck from "../components/Truck.vue";
import Services from "../components/Services.vue";
import About from "../components/About.vue";
import Why from "../components/Why.vue";
import Testmonials from "../components/Testmonials.vue";
import Blog from "../components/Blog.vue";
import Contact from "../components/Contact.vue";
import Social from "../components/Social.vue";

export default {
  name: "Home",
  components: {
    Header,
    Truck,
    Services,
    About,
    Why,
    Testmonials,
    Blog,
    Contact,
    Social,
  }
};
import "../../node_modules/jquery/dist/jquery.min.js";
import $ from "jquery";
$(document).ready(function() {
  $(window).scroll(function() {
    if ($(this).scrollTop() > 400) {
      $(".top").css({
        "visibility": "visible",
      });
    }
     else {
      $(".top").css({
        "visibility": "hidden",
      });
    }
  });
  $('.top').click(function () { 
    $('html,body').animate({scrollTop:0},"fast")
  });
    
});
</script>
<style lang="scss" scoped>
.home{
  .top{
    position: fixed;
    top: 90%;
    z-index: 22;
    right: 30px;
    visibility: hidden;
    cursor: pointer;
    span{
      i{
        color: #ffffff;
    padding: 15px;
    border-radius: 10px;
    background-color: #1169c1;
      }
    }
  }
}
</style>
