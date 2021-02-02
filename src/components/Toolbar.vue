<template>
    <div class="toolbar" id="Home">
        <div class="container">
            <div class="row">
                <div class="left d-flex col-lg-8 col-sm-12 col-md-8 row mx-auto">
                    <div class="email mx-auto" data-aos="fade-down" data-aos-duration="1000">
                        <span ><i class="far fa-envelope-open"></i></span>
                        
                        info@yourdomain.com
                    </div>
                    <div class="phone mx-auto" data-aos="fade-up" data-aos-duration="1000">
                        <span><i class="fas fa-phone"></i></span>
                        1+ (234) 5678 9101
                    </div>
                </div>
                <div class="right d-flex col-lg-4 col-sm-12 col-md-4">
                   <div class="twitter mx-auto" data-aos="fade-up" data-aos-duration="1000">
                       <span><i class="fab fa-twitter"></i></span>
                       twitter
                   </div>
                   <div class="facbook mx-auto" data-aos="fade-down" data-aos-duration="1000">
                       <span><i class="fab fa-facebook-f"></i></span>
                       facbook
                   </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>

export default {
    name:'Toolbar',
    
}
</script>
<style lang="scss" scoped>
    .toolbar{
        background-color: rgb(238, 238, 238);
        padding: 10px;
        color: rgb(102, 102, 102);
        font-size: 17px;
        .container{
            .row{
                i{
                    padding-right: 5px;
                }
                .left{
                    .email{
                        margin-right: 80px;
                        cursor: pointer;
                    }
                    .phone{
                        cursor: pointer;
                    }
                }
                .right{
                    text-transform: capitalize;
                    .twitter{
                        // margin-right: 100px;
                        // margin-left: 60px;
                        cursor: pointer;
                    }
                    .facbook{
                        cursor: pointer;
                    }
                }
            }
        }
    }
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .phone{
        margin: 7px 0px;
    }
    .toolbar{
        display: none;
    }
}    
</style>