<template>
    <div class="offer">
        <div class="container">
            <div class="tryFreeItems">
                <a href="#" class="tryFreeBtn">TRY FREE</a>
                <div class="tryFreeText">With demo account</div>
            </div>
            <h1>The best platform to learn and invest in crypto</h1>
            <div class="subH1">Buy and sell cryptocurrencies, earn money and gain experience.</div>
            <a href="" class="tryItNowItems">
                <div class="tryItNowText">Try it now</div>
                <div class="tryItNowImageContainer">
                    <img src="../assets/images/left-arrow.svg" alt="just arrow">
                </div>
            </a>
        </div>
    </div>
</template>

<script>
    export default {
        name: "offer"
    }
</script>

<style lang="scss" scoped>
    @import "../assets/styles/variables.scss";
    .offer{
        background: url(../assets/images/first-view-image.svg) no-repeat right bottom;
        -webkit-background-size: contain;
        background-size: contain;
        height: 100vh;
        .container{
            padding-top: 130px;
            .tryFreeItems{
                box-sizing: border-box;
                width: 100%;
                max-width: 353px;
                display: flex;
                height: 39px;
                padding: 4px;
                border-radius: 100px;
                background-color: $colorTryFree;
                align-items: center;
                .tryFreeBtn{
                    width: 108px;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    @include fontRubik(500);
                    text-decoration: none;
                    color: $colorTryFreeText;
                    background-color: $colorTryFreeBtn;
                    height: 31px;
                    border-radius: 100px;
                    font-size: 16px;
                }
                .tryFreeText {
                    color: #fff;
                    @include fontRubik(400);
                    margin-left: 18px;
                    font-size: 16px;
                }
            }
            h1 {
                font-size: 55px;
                max-width: 600px;
                @include fontPoppins(700);
                color: #fff;
                margin-top: 25px;
            }
            .subH1{
                color: #fff;
                margin-top: 13px;
                @include fontRubik(400);
                font-size: 16px;
                max-width: 435px;
            }
            .tryItNowItems{
                box-sizing: border-box;
                width: 184px;
                height: 65px;
                margin-top: 50px;
                display: flex;
                justify-content: space-between;
                align-items: center;
                @include fontPoppins(600);
                font-size: 18px;
                text-decoration: none;
                color: #fff;
                background-color: $lightBlue;
                border-radius: 100px;
                padding: 0 16px 0 24px;
                .tryItNowImageContainer{
                    width: 32px;
                    height: 32px;
                    border-radius: 50%;
                    background-color: #fff;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                }
            }
        }

    }
</style>