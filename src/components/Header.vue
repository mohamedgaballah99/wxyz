<template>
  <div class="header">
    <div class="container">
      <div class="info">
        <h1 class="ani" data-aos="zoom-in-up" data-aos-duration="1500" data-aos-delay="300">
          TRANSPORTATIONS &<br> LOGISTICS
        </h1>
        <p data-aos="fade-right" data-aos-duration="800" data-aos-delay="100">
          Far far away, behind the word mountains, far from the countries<br>
          Vokalia and Consonantia, there live the blind texts.
        </p>
        <form>
            <input type="text" placeholder="Your Traking Number"  data-aos="fade-right" data-aos-duration="800" data-aos-delay="100">
            <button  data-aos="fade-left" data-aos-duration="800" data-aos-delay="50">Track Now</button>
        </form>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name:'Header'
}
</script>
<style lang="scss" scoped>
    .header{
        background-image: url("../assets/images/header.jpg");
        background-size: 100% 100%;
        background-repeat: no-repeat;
        height: 100vh;
        color: white;
        .container{
            padding: 30px 0px;
            .info{
                position: absolute;
                top: 50%;
                left: 30%;
                text-align: center;
                
                h1{
                    font-size: 48px;
                    font-weight: bold;
                }
                p{
                    font-size: 20px;
                    margin: 30px 0px;
                }
                form{
                    input{
                        border: none;
                        font-size: 18px;
                        outline: none;
                        padding: 15px 20px;
                        width: 400px;
                        transition: 0.5s all;
                        margin-right: 10px;
                        &:focus{
                            box-shadow: 0px 0px 10px #007bff;
                        }
                    }
                    button{
                        border: none;
                        background-color: #007bff;
                        padding: 15px;
                        color: white;
                        &:hover{
                            opacity: 0.9;
                        }
                    }
                }
            }
        }
    }
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .header{
       .container{
            .info{
                left: 0%;
                 font-family: 'Courier New', Courier, monospace;
                h1{
                    font-size: 30px;
                }
                p{
                    font-size: 18px;
                    margin: 30px 10px;
                }
                form{
                    input{
                        font-size: 15px;
                        padding: 10px 15px;
                        width: 200px;
                    }
                     button{
                        padding: 9px;                        
                    }
                }
            }
       }
    }
}    
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
    .header{
       .container{
            .info{
                left: 1%;
                margin: 3px;
                 font-family: 'Courier New', Courier, monospace;
                h1{
                    font-size: 37px;
                }
                p{
                    font-size: 20px;
                }
                form{
                    input{
                        font-size: 15px;
                        padding: 13px 18px;
                        width: 350px;
                    }
                     button{
                        padding: 11px;                        
                    }
                }
            }
       }
    }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
        .header{
       .container{
            .info{
                left: 4%;
                 font-family: 'Courier New', Courier, monospace;
                h1{
                    font-size: 47px;
                }
                p{
                    font-size: 25px;
                }
            }
       }
    }
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
    .header{
       .container{
            .info{
                left: 15%;
                 font-family: 'Courier New', Courier, monospace;
                h1{
                    font-size: 47px;
                }
                p{
                    font-size: 25px;
                }
            }
       }
    }
}

</style>
