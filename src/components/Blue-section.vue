<template>
    <div class="options">
        <div class="container">

            <div>
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>

            <div>
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>
            
            <div>
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>

            <div>
                <img src="../assets/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATION</span>
            </div>

            <div>
                <img src="../assets/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'BlueSection'


}
</script>

<style lang="scss" scoped>

@import '../style/colors';
@import '../style/fonts';

    .options {
        background-color: $section-color;
        display: flex;
        align-items: center;
        padding: 50px 0;

        .container {
            justify-content: space-around;

            div {
                width: 18%;
                font-size: $font-small;

                &:last-child {
                    
                    img {
                        width: 30%;
                    }
                }

                span {
                    margin-left: 15px;
                    color: $text-color;
                }
    
                img {
                    height: 60px;
                    vertical-align: middle;
                }
            }
        }
    }


</style>