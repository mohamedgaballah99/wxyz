<template>
  <div class="about">
    <div class="info" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200">
      <h1>about us</h1>
      <p>
        Far far away, behind the word mountains, far from the countries Vokalia
        and Consonantia, <br />there live the blind texts.
      </p>
    </div>
    <div class="container">
      <div class="vedio" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="200">
        <img src="../assets/images/vedio.jpg" />
        <span data-toggle="modal" data-target="#myModal"
          ><i class="fas fa-play"></i
        ></span>
        <!-- The Modal -->
        <div class="modal" id="myModal" style="z-index:99999999999">
          <div class="modal-dialog">
            <div class="modal-content">
              <!-- Modal Header -->
              <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal">
                  &times;
                </button>
              </div>

              <!-- Modal body -->
              <div class="modal-body">
                <iframe
                  width="100%"
                  height="100%"
                  src="https://www.youtube.com/embed/9npIk-SY3Y0"
                  frameborder="0"
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture;"
                  allowfullscreen
                ></iframe>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="num">
        <div class="row">
          <div class="col-sm-12 col-md-6 col-lg-3" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="200">
            <span class=" d-flex "
              ><VueJsCounter start="0" end="19" duration="25000"></VueJsCounter
              >+</span
            >
            <span><i class="fas fa-briefcase"></i></span>
            <span>Years in Service</span>
          </div>

          <div class="col-sm-12 col-md-6 col-lg-3" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200">
            <span class=" d-flex "
              ><VueJsCounter
                start="0"
                end="2332"
                duration="25000"
                thousand=","
              ></VueJsCounter
              >+</span
            >
            <span><i class="fas fa-users"></i></span>
            <span> Employees </span>
          </div>

          <div class="col-sm-12 col-md-6 col-lg-3" data-aos="fade-left" data-aos-duration="1000" data-aos-delay="200">
            <span class=" d-flex "
              ><VueJsCounter start="0" end="231" duration="25000"></VueJsCounter
              >+</span
            >
            <span><i class="fas fa-globe-americas"></i></span>
            <span>Covered Countries</span>
          </div>

          <div class="col-sm-12 col-md-6 col-lg-3" data-aos="fade-down" data-aos-duration="1000" data-aos-delay="200">
            <span class=" d-flex "
              ><VueJsCounter start="0" end="827" duration="25000"></VueJsCounter
              >+</span
            >
            <span><i class="fas fa-smile-beam"></i></span>
            <span>Couriers</span>
          </div>
        </div>
      </div>

      <div class="staff">
        <div class="info" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200">
          <h1>Our Staff</h1>
          <p>
            Far far away, behind the word mountains, far from the countries
            Vokalia and Consonantia,<br />
            there live the blind texts.
          </p>
        </div>
        <div class="row">
          <div class="col-sm-12 col-md-6 col-lg-4" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="200">
            <div class="img">
              <img src="../assets/images/person1.jpg" />
            </div>
            <h3>MAX CARLSON</h3>
            <span>CO-FOUNDER</span>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
            <i class="fab fa-facebook-square"></i>
            <i class="fab fa-twitter"></i>
            <i class="fab fa-instagram"></i>
          </div>

          <div class="col-sm-12 col-md-6 col-lg-4" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200">
            <div class="img">
              <img src="../assets/images/person2.jpg" />
            </div>
            <h3>CHARLOTTE PILAT</h3>
            <span>CO-FOUNDER</span>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
            <i class="fab fa-facebook-square"></i>
            <i class="fab fa-twitter"></i>
            <i class="fab fa-instagram"></i>
          </div>

          <div class="col-sm-12 col-md-12 col-lg-4" data-aos="fade-left" data-aos-duration="1000" data-aos-delay="200">
            <div class="img">
              <img src="../assets/images/person3.jpg" />
            </div>
            <h3>NICOLE LEWIS</h3>
            <span>CO-FOUNDER</span>
            <p>
              Far far away, behind the word mountains, far from the countries
              Vokalia and Consonantia, there live the blind texts.
            </p>
            <i class="fab fa-facebook-square"></i>
            <i class="fab fa-twitter"></i>
            <i class="fab fa-instagram"></i>
          </div>
        </div>
      </div>

      <div class="price">
        <div class="info" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200">
          <h1>Pricing</h1>
          <p>
            Far far away, behind the word mountains, far from the countries
            Vokalia and Consonantia,<br />
            there live the blind texts.
          </p>
        </div>
        <div class="row text-center">
          <div class="col-sm-12 col-md-6 col-lg-4" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="200">
            <h3>BASIC</h3>
            <h1>$47<span>/ year</span></h1>
            <ul class="text-left">
           <li><i class="fas fa-check"></i> Officia quaerat eaque neque</li>
             <li><i class="fas fa-check"></i> Possimus aut consequuntur incidunt</li>
             <li><i class="fas fa-check"></i> Lorem ipsum dolor sit amet</li>
             <li><i class="fas fa-check"></i> Consectetur adipisicing elit</li>
              <li><i class="fas fa-check"></i> Dolorum esse odio quas architecto sint</li>
            </ul>
            <button>buy now</button>
          </div>

          <div class="col-sm-12 col-md-6 col-lg-4" data-aos="fade-down" data-aos-duration="1000" data-aos-delay="200">
            <h3>PREMIUM</h3>
            <h1>$200<span>/ year</span></h1>
            <ul class="text-left">
              <li><i class="fas fa-check"></i> Officia quaerat eaque neque</li>
             <li><i class="fas fa-check"></i> Possimus aut consequuntur incidunt</li>
             <li><i class="fas fa-check"></i> Lorem ipsum dolor sit amet</li>
             <li><i class="fas fa-check"></i> Consectetur adipisicing elit</li>
              <li><i class="fas fa-check"></i> Dolorum esse odio quas architecto sint</li>
            </ul>
            <button>buy now</button>
          </div>

          <div class="col-sm-12 col-md-6 col-lg-4" data-aos="fade-left" data-aos-duration="1000" data-aos-delay="200">
            <h3>PROFESSIONAL</h3>
            <h1>$750<span>/ year</span></h1>
            <ul class="text-left">
              <li><i class="fas fa-check"></i> Officia quaerat eaque neque</li>
             <li><i class="fas fa-check"></i> Possimus aut consequuntur incidunt</li>
             <li><i class="fas fa-check"></i> Lorem ipsum dolor sit amet</li>
             <li><i class="fas fa-check"></i> Consectetur adipisicing elit</li>
              <li><i class="fas fa-check"></i> Dolorum esse odio quas architecto sint</li>
            </ul>
            <button>buy now</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import "../../node_modules/jquery/dist/jquery.min.js";
import VueJsCounter from "vue-js-counter";

import $ from "jquery";
$(document).ready(function() {
  $(".close").click(function() {
    $("iframe").attr("src", " ");
  });
});
export default {
  name: "About",
  components: {
    VueJsCounter,
  },
};
</script>
<style lang="scss" scoped>
.about {
  margin-top: 80px;
  .info {
    text-align: center;
    h1 {
      color: #007bff;
      text-transform: capitalize;
      font-family: "Courier New", Courier, monospace;
      font-weight: bold;
    }
    p {
      color: gray;
      line-height: 1.8;
      font-family: "Courier New", Courier, monospace;
    }
  }
  .container {
    .vedio {
      width: 100%;
      position: relative;
      img {
        width: 100%;
        cursor: pointer;
      }
      span {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        i {
          color: #007bff;
          background-color: white;
          padding: 40px;
          border-radius: 50%;
          font-size: 15px;
          cursor: pointer;
          transition: 0.5s all;
          animation: scal 2s infinite;
        }
      }
      .modal-content {
        height: 600px !important;
        .modal {
          position: absolute;
          top: 50%;
          left: 50%;
          transform: translate(-50%, -50%);
        }
      }
    }
    .num {
      margin-top: 40px;
      background-color: rgba(230, 230, 230, 0.377);
      padding: 20px;
      margin-bottom: 50px;
      .row {
        > div {
          margin-bottom: 50px;

          span {
            display: block;
            text-align: center;
          }
          span:first-of-type {
            color: rgb(10, 20, 151);
            font-size: 50px;
            font-family: "Raleway", -apple-system, BlinkMacSystemFont,
              "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans",
              sans-serif, "Apple Color Emoji", "Segoe UI Emoji",
              "Segoe UI Symbol", "Noto Color Emoji";
          }
          span:nth-of-type(2) {
            color: #007bff;
            font-size: 35px;
          }
          span:last-of-type {
            color: black;
            font-size: 23px;
            font-family: "Courier New", Courier, monospace;
          }
        }
        div:first-of-type {
          span:first-of-type {
            margin-left: 85px;
          }
        }
        div:nth-of-type(2) {
          span:first-of-type {
            margin-left: 60px;
          }
        }
        div:nth-of-type(3) {
          span:first-of-type {
            margin-left: 70px;
          }
        }
        div:last-of-type {
          span:first-of-type {
            margin-left: 70px;
          }
        }
      }
    }
    .staff {
      margin-bottom: 100px;
      .row {
        > div {
          text-align: center;
          font-family: "Courier New", Courier, monospace;
          margin-top: 100px;
          transition: 0.5s all;
          padding: 10px;
          &:hover {
            box-shadow: 0px 0px 20px rgba(128, 128, 128, 0.582);
          }
          .img {
            width: 160px;
            margin: 20px auto;

            img {
              width: 100%;
              border-radius: 50%;
            }
          }
          h3 {
            color: #007bff;
            font-weight: bold;
          }
          span {
            color: gray;
          }
          p {
            color: gray;
            margin: 10px;
          }
          i {
            background-color: #007bff;
            color: white;
            cursor: pointer;
            padding: 10px !important;
            margin: 5px;
            border: 1px solid transparent;
            transition: 0.5s all;
            &:hover {
              border: 1px solid #007bff;
              background-color: white;
              color: #007bff;
            }
          }
        }
        div:nth-last-of-type(2) {
          border-left: 1px solid rgba(128, 128, 128, 0.384);
          border-right: 1px solid rgba(128, 128, 128, 0.384);
        }
      }
    }
    .price {
      margin-bottom: 100px;
      .row {
        > div {
          text-align: center;
          font-family: "Courier New", Courier, monospace;
          margin-top: 100px;
          transition: 0.5s all;
          padding: 10px;
          &:hover {
            box-shadow: 0px 0px 20px rgba(128, 128, 128, 0.582);
          }
          h3 {
            color: black;
            font-weight: 600;
          }
          h1 {
            color: #007bff;
            font-weight: bold;
            margin: 30px 0px;
            span {
              color: rgba(128, 128, 128, 0.589);
              font-size: 20px;
            }
          }
          ul {
            list-style: none;
            margin: 30px;
            li {
              margin: 20px 0px;
               i{
              color: #71bc42;
              padding: 0px !important;
            }
            }
          }
          button {
            background-color: #007bff;
            color: white;
            border: none;
            margin-top: 20px;
            padding: 10px 15px;
            text-transform: capitalize;
            transition: 0.5s all;
            border: 1px solid transparent;
            &:hover {
              border: 1px solid #007bff;
              background-color: white;
              color: #007bff;
            }
          }
        }
        div:nth-last-of-type(2) {
          border-left: 1px solid rgba(128, 128, 128, 0.384);
          border-right: 1px solid rgba(128, 128, 128, 0.384);
        }
      }
    }
  }
}
@keyframes scal {
  0% {
    transform: scale(1.2);
  }
  50% {
    transform: scale(1);
  }
  100% {
    transform: scale(1.2);
  }
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  i {
    padding: 16px !important;
  }
  .num {
    .row {
      div:first-of-type {
        span:first-of-type {
          margin-left: 110px !important;
        }
      }
      div:nth-of-type(2) {
        span:first-of-type {
          margin-left: 80px !important;
        }
      }
      div:nth-of-type(3) {
        span:first-of-type {
          margin-left: 110px !important;
        }
      }
      div:last-of-type {
        span:first-of-type {
          margin-left: 110px !important;
        }
      }
    }
  }
  .price{
    div:nth-last-of-type(2) {
          border-left: none !important;
          border-right: none !important;
        }
  }
  .staff{
    div:nth-last-of-type(2) {
          border-left: none !important;
          border-right: none !important;
        }
  }
  .vedio{
    width: 90% !important;
    margin: auto;
    img{
      width: 100% !important;
    }
  }
}
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  i {
    padding: 30px !important;
  }
  .num {
    .row {
      div:first-of-type {
        span:first-of-type {
          margin-left: 110px !important;
        }
      }
      div:nth-of-type(2) {
        span:first-of-type {
          margin-left: 80px !important;
        }
      }
      div:nth-of-type(3) {
        span:first-of-type {
          margin-left: 110px !important;
        }
      }
      div:last-of-type {
        span:first-of-type {
          margin-left: 110px !important;
        }
      }
    }
  }
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .num {
    .row {
      div:first-of-type {
        span:first-of-type {
          margin-left: 60px !important;
        }
      }
      div:nth-of-type(2) {
        span:first-of-type {
          margin-left: 40px !important;
        }
      }
      div:nth-of-type(3) {
        span:first-of-type {
          margin-left: 60px !important;
        }
      }
      div:last-of-type {
        span:first-of-type {
          margin-left: 60px !important;
        }
      }
    }
  }
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
  .num {
    .row {
      div:first-of-type {
        span:first-of-type {
          margin-left: 80px !important;
        }
      }
      div:nth-of-type(2) {
        span:first-of-type {
          margin-left: 50px !important;
        }
      }
      div:nth-of-type(3) {
        span:first-of-type {
          margin-left: 75px !important;
        }
      }
      div:last-of-type {
        span:first-of-type {
          margin-left: 75px !important;
        }
      }
    }
  }
}
</style>
