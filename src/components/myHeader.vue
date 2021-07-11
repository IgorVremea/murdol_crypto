<template>
    <header>
        <div class="container">
            <div class="left">
                <a href="#" class="logoItems">
                    <img src="../assets/images/logo.svg" alt="logo">
                    <div class="logoText">MURDOL CRYPTO</div>
                </a>
            </div>
            <div class="right">
               <nav>
                   <a href="#" class="about">About</a>
                   <a href="#" class="contact">Contact</a>
               </nav>
               <div class="loginItems">
                   <a href="#" class="login">Login</a>
                   <div class="line"></div>
                   <a href="#" class="register">Register</a>
               </div>
            </div>
        </div>
    </header>
</template>

<script>
    export default {
        name: "myHeader"
    }
</script>

<style lang="scss" scoped>
    @import '../assets/styles/variables.scss';
    header{
        height: 52px;
        padding-top: 60px;
        .container{
            display: flex;
            justify-content: space-between;
            align-items: center;
            .left {
                .logoItems {
                    display: flex;
                    align-items: center;
                    @include fontInter(600);
                    text-decoration: none;
                    color: #fff;
                    font-size: 18px;

                    img {
                        width: 40px;
                        margin-right: 16px;
                    }
                }
            }
            .right{
                display: flex;
                @include fontRubik(400);
                font-size: 16px;
                align-items: center;
                a{
                    text-decoration: none;
                    color: #fff;
                }
                nav{
                    margin-right: 56px;
                    .about{
                      margin-right: 32px;
                    }
                    .contact{
                    }
                }
                .loginItems{
                    display: flex;
                    align-items: center;
                    .login{
                        margin-right: 24px;
                    }
                    .line {
                        height: 24px;
                        width: 1px;
                        background-color: $grayLoginLine;
                    }
                    .register{
                        display: flex;
                        align-items: center;
                        justify-content: center;
                        width: 130px;
                        height: 52px;
                        border-radius: 100px;
                        background-color: $lightBlue;
                        margin-left: 24px;
                    }
                }

            }
        }
    }
</style>