<template>
    <div class="blog">
         <div class="container">
             <h1>Articles</h1>
             <div class="row">
                 <div class="col-sm-12 col-md-12 col-lg-6" data-aos="fade-right" data-aos-duration="1000" data-aos-delay="200">
                     <div class="img">
                         <img src="../assets/images/1.jpg" alt="">
                     </div>
                     <h6>Apr 19, 2019</h6>
                     <h2>KNOWING THE DIFFERENCE IS KEY TO EFFECTIVE LOGISTICS</h2>
                     <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts</p>
                     <button class="btn">read more</button>
                 </div>

                 <div class="col-sm-12 col-md-12 col-lg-6" data-aos="fade-left" data-aos-duration="1000" data-aos-delay="200">
                     <div class="img">
                         <img src="../assets/images/2.jpg" alt="">
                     </div>
                     <h6>Apr 19, 2019</h6>
                     <h2>KNOWING THE DIFFERENCE IS KEY TO EFFECTIVE LOGISTICS</h2>
                     <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts</p>
                     <button class="btn">read more</button>
                 </div>

             </div>
         </div>   
    </div>
</template>
<script>
export default {
    name:'blog',
}
</script>
<style lang="scss" scoped>
    .blog{
        margin-bottom: 50px;
        .container{
            font-family: 'Courier New', Courier, monospace;
            h1{
                color: #007bff;
                font-weight: bold;
                text-align: center;
                padding-top: 50px;
                padding-bottom: 50px;
            }
            .row{
                >div{
                    .img{
                        width: 100%;
                        img{
                            width: 100%;
                        }
                    }
                    h6{
                        padding-top: 7px;
                        color: gray;
                    }
                    h2{
                        transition: 0.5s all;
                        cursor: pointer;
                        margin: 20px 0px;
                        &:hover{
                            color: #007bff;
                        }
                    }
                    
                    button{
                        color: #007bff;
                        text-transform: capitalize;
                    }
                }
            }
        }
    }
    /* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .row{
        h2{
            font-size: 18px !important;
        }
        p{
            font-size: 15px;
        }
    }
}
</style>