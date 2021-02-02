<template>
    <div class="contact">
        <div class="container">
            <h1>Contact Us</h1>
            <div class="form">
                <form>
                    <input type="text" placeholder="First name" style="margin-right:20px">
                    <input type="text" placeholder="Last name"><br>
                    <input type="email" placeholder="Email address"><br>
                    <textarea cols="30" rows="5" placeholder="Message"></textarea><br>
                    <button class="btn">Send</button>
                </form>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'contact',
}
</script>
<style lang="scss" scoped>
.contact{
    background-color: #d0d0d444;
    .container{
        font-family: 'Courier New', Courier, monospace;
        h1{
            font-weight: bold;
            color: #007bff;
            padding: 30px 0px;
            text-align: center;
        }
        .form{
            form{
                margin: auto;
                width: 60%;
                input{
                    border: none;
                    outline: none;
                    padding: 20px;
                    margin: 20px 0px;
                    transition: 0.5s all;
                    border: 1px solid transparent;
                    &:hover{
                        border: 1px solid #007bff;
                    }
                }
                 input[type="text"]{
                    width: 48.5%;
                }
                input[type="email"]{
                    width: 100%;
                }
                textarea{
                    width: 100%;
                    margin-bottom: 20px;
                    border: none;
                    outline: none;
                    padding: 20px;
                    transition: 0.5s all;
                    border: 1px solid transparent;
                    &:hover{
                        border: 1px solid #007bff;
                    }
                }
                button{
                    background-color: #007bff;
                    color: white;
                    padding: 10px 40px;
                    text-transform: uppercase;
                    font-weight: bold;
                    margin-bottom: 30px;
                    transition: 0.5s all;      
                    border: 1px solid transparent;

                    &:hover{
                        background-color: white;
                        color: #007bff;         
                        border: 1px solid #007bff;

                    }
                }
            }
        }
    }
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
form{
    width: 90% !important;
    input{
        padding: 15px !important;
    }
    input[type="text"]{
        width: 100% !important;
    }
}
}


/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
form{
    input{
        padding: 10px 15px !important;
    }
    input[type="text"]{
        width: 47.5% !important;
    }
}
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
form{
    input[type="text"]{
        width: 48% !important;
    }
}
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
    form{
    input[type="text"]{
        width: 48.5% !important;
    }
}
}
</style>