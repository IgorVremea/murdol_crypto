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
            padding: 117px 0 0 120px;
            .img{
                width: 394px;
            }
        }

    }
</style>