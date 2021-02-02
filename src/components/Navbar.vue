<template>
  <div class="navbar">
    <div class="container">
      <div class="logo">
        Depot
      </div>
      <span><i class="fas fa-bars open"></i> </span>

      <div class="list">
        <ul>
          <li><a href="#Home">Home</a></li>
          <li><a href="#Services">Services</a></li>
          <li><a href="#AboutUs">About Us</a></li>
          <li><a href="#WhyUs">Why Us</a></li>
          <li><a href="#Testimonials">Testimonials</a></li>
          <li><a href="#Blog">Blog</a></li>
          <li><a href="#Contact">Contact</a></li>
        </ul>
        <span><i class="far fa-times-circle close"></i></span>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "navbar",
};
import "../../node_modules/jquery/dist/jquery.min.js";
import $ from "jquery";
$(document).ready(function() {
  $(window).scroll(function() {
    if ($(this).scrollTop() > 100) {
      $(".navbar").css({
        "background-color": "white",
        "position": "fixed",
        "top": "0px" ,
        "left": "0px",
        "right": "0px",
        "transition":"0.5s all"
      });
    }
     else {
      $(".navbar").css({
        "background-color": "transparent",
        "position": "fixed",
        "top": "33px",
        "left": "0px",
        "right": "0px",
      });
    }
  });
  $('.open').click(function () { 
        $('.list').fadeIn('slow');
    });
    $('.close').click(function () { 
        $('.list').fadeOut('slow');
        
    });
    $('.list ul li a').click(function () { 
        $('.list').fadeOut('slow');        
    });
    
});
</script>
<style lang="scss" scoped>
.navbar {
  background-color: transparent;
  position: fixed;
  top: 33px;
  left: 0px;
  right: 0px;
  padding: 10px;
  z-index: 9999;
  .container {
    .logo {
      color: #007bff;
      font-weight: bold;
      font-size: 40px;
      text-transform: uppercase;
    }
    span {
      .open {
        color: #007bff;
        font-size: 35px;
        cursor: pointer;
      }
    }
    .list {
      background-color: #02435b;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 100%;
      height: 100vh;
      display: none;
      animation: nav 2s ease-in-out;
      z-index: 222;
      ul {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        list-style: none;
        li {
          margin: 35px 0px;
          a {
            color: white;
            font-size: 25px;
            font-weight: bold;
            font-family: monospace;
            text-decoration: none;
            transition: 0.5s all;
            &:hover {
              color: #007bff;
              text-shadow: 0px 0px 10px #05bcff;
            }
          }
        }
      }
      span {
        i {
          color: white;
          font-size: 35px;
          cursor: pointer;
          position: fixed;
          top: 40px;
          right: 40px;
          text-shadow: 0px 0px 30px #05bcff;
        }
      }
    }
  }
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  .navbar {
    top: 0px !important;
  }
  .logo {
    font-size: 32px !important;
  }
  .open {
    font-size: 30px !important;
  }
  .list {
    span {
      i {
        font-size: 30px !important;
      }
    }
  }
}
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .logo {
    font-size: 37px !important;
  }
  .open {
    font-size: 30px !important;
  }
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .logo {
    font-size: 40px !important;
  }
  .open {
    font-size: 35px !important;
  }
}
@keyframes nav {
  from {
    width: 0px;
  }
  to {
    width: 100%;
  }
}
</style>
