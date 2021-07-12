<template>
    <div class="advantages">
        <div class="container">
            <div class="numbers">
                <div class="item currency">
                    <div class="imgContainer">
                        <img src="../assets/images/advantagesGrafic.svg" alt="grafic">
                    </div>
                    <div class="text">
                        <div class="heading">$30B</div>
                        <div class="subheading">Crypto Currency Exchanged</div>
                    </div>
                </div>
                <div class="item person">
                    <div class="imgContainer">
                        <img src="../assets/images/advantagesPerson.svg" alt="person">
                    </div>
                    <div class="text">
                        <div  class="heading">10M+</div>
                        <div class="subheading">Satisfied users</div>
                    </div>
                </div>
                <div class="item earth">
                    <div class="imgContainer">
                        <img src="../assets/images/advantagesEarth.svg" alt="earth">
                    </div>
                    <div class="text">
                        <div class="heading">195</div>
                        <div class="subheading">Every country is supported </div>
                    </div>
                </div>
            </div>
            <div class="mainSection">
                <img src="../assets/images/advantagesMain.png" alt="a person" class="left">
                <div class="right">
                    <h2>Why you should choose Murdol Crypto</h2>
                    <div class="subHeading">Experience the next generation cryptocurrency platform. No financial borders, extra fees, and fake reviews. Demo account.</div>
                    <a href="#" class="learnMore">Learn More</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "advantages"
    }
</script>

<style lang="scss" scoped>
    @import '../assets/styles/variables.scss';
    .advantages {
        background: url("../assets/images/advantagesLeftBottom.svg") no-repeat, url("../assets/images/advantagesD.svg") no-repeat, url("../assets/images/advantagesU.svg") no-repeat;
        background-position: left 100%, right 30%, right 90%;
        background-color: $darkBlueBgColor;

        .numbers{
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding-top: 100px;
            .item{
                display: flex;
                align-items: flex-start;
                .imgContainer{
                    width: 80px;
                    height: 80px;
                    background-color: $colorTryFree;
                    border-radius: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    img{
                        width: 40px;
                    }
                }
                .text{
                    margin-left: 24px;
                    @include fontPoppins(400);
                    color: #fff;
                    .heading{
                        font-size: 40px;
                        font-weight: 700;
                        margin-bottom: 4px;
                    }
                }
            }
        }
        .mainSection{
            box-sizing: border-box;
            padding: 117px 0 0 120px;
            display: flex;
            justify-content: space-between;
            width: 100%;
            .left{
                width: 394px;
            }
            .right{
                width: 480px;
                color: white;
                padding-top: 60px;
                @include fontPoppins(400);
                h2{
                    font-size: 40px;
                }
                .subH1{
                    margin-top: 23px;
                }
                .learnMore{
                    display:inline-block;
                    margin-top: 48px;
                    padding: 16px 24px;
                    color: white;
                    text-decoration: none;
                    @include fontPoppins(600);
                    background-color: $lightBlue;
                    border-radius: 100px;
                }

            }
        }

    }
</style>