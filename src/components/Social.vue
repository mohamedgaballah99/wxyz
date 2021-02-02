<template>
  <div class="social">
    <div class="container">
      <div class="row">
        <div class="col-sm-12 col-md-4 col-lg-5">
          <h4>FEATURES</h4>
          <ul>
            <li><a href="#Home">Home</a></li>
            <li><a href="#Services">Services</a></li>
            <li><a href="#AboutUs">About Us</a></li>
            <li><a href="#WhyUs">Why Us</a></li>
            <li><a href="#Testimonials">Testimonials</a></li>
            <li><a href="#Blog">Blog</a></li>
            <li><a href="#Contact">Contact</a></li>
          </ul>
        </div>

        <div class="col-sm-12 col-md-5 col-lg-5">
          <h4>SUBSCRIBE TO NEWSLETTER</h4>
          <input type="email" placeholder="Enter Email"/>
          <button class="btn btn-primary">SUBSCRIBE</button>
          <div class="icons">
              <h4>FOLLOW US</h4>
          <span><i class="far fa-envelope-open"></i></span>
          <span><i class="fas fa-phone"></i></span>
          <span><i class="fab fa-twitter"></i></span>
          <span><i class="fab fa-facebook-f"></i></span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "social",
};
</script>
<style lang="scss" scoped>
.social {
  background-color: rgba(0, 0, 0, 0.815);
  font-family: 'Courier New', Courier, monospace;
  .container {
      padding: 50px 0px;
    .row {
      > div {
        h4 {
            font-weight: bold;
            color: white;
            padding-bottom: 10px;
        }
        ul {
            list-style: none;
          li {
              margin: 10px 0px;
            a {
                color: white;
                transition: 0.5s all;
                text-decoration: none;
                
                &:hover{
                    color:#007bff;
                }

            }
          }
        }
        input{
            border: none;
            outline: none;
            padding: 13px 20px;
            width: 350px;
            margin-right: 10px;
        }
        button{
            font-size: 20px;
            padding: 9px 10px;
        }
        .icons{
            margin-top: 30px;
            span{
            i{
                color: white;
                 transition: 0.5s all;
                cursor: pointer;
                margin-right: 30px;
                &:hover{
                    color:#007bff;
                }
            }
        }
        }
        
      }
    }
  }
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .row{
        >div{
            margin: 40px;
            text-align: center;
            input{
                width: 270px !important;
                margin-bottom: 10px;
                margin-right: 0px !important;
            }
            button{
                font-size: 16px !important;
            }
            h4{
                font-size: 18px;
            }
            .icons{
                span:first-of-type{
                    margin-left: 30px;
                }
            }
        }
    }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
        .row{
        >div{
            margin: 40px;
            text-align: left;
            input{
                width: 270px !important;
                margin-bottom: 10px;
                margin-right: 0px !important;
            }
            button{
                font-size: 16px !important;
            }
            h4{
                font-size: 20px;
            }
            .icons{
                span:first-of-type{
                    margin-left: 0px !important;
                }
            }
        }
    }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
       .row{
        >div{
            margin: 40px;
            text-align: left;
            input{
                width: 250px !important;
                margin-bottom: 10px;
                margin-right: 10px !important;
            }
            button{
                font-size: 16px !important;
                padding: 12px 10px !important;
            }
            h4{
                font-size: 20px;
            }
            .icons{
                span:first-of-type{
                    margin-left: 0px !important;
                }
            }
        }
    }
}
</style>
