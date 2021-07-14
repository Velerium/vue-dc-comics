<template>
    <div class="bg-color">
        <div class="container">

            <div class="button-bottom">SIGN UP NOW!</div>

            <div class="social-links">
                <span>FOLLOW US</span>
                <div>
                    <img src="../assets/footer-facebook.png" alt="">
                </div>
                
                <div>
                    <img src="../assets/footer-twitter.png" alt="">
                </div>

                <div>
                    <img src="../assets/footer-youtube.png" alt="">
                </div>

                <div>
                    <img src="../assets/footer-pinterest.png" alt="">
                </div>

                <div>
                    <img src="../assets/footer-periscope.png" alt="">
                </div>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'BottomSection',


}
</script>

<style lang="scss" scoped>

@import '../style/colors';

.bg-color {
    background-color: $bottom-color;

    .container {
        justify-content: space-between;
        align-items: center;
        padding: 40px 0;

        .button-bottom {
            padding: 10px 15px;
            color: $text-color;
            border: 2px solid $section-color;
        }

        .social-links {
            display: flex;
            align-items: center;

            span {
                color: $section-color;
                font-size: 18px;
                margin-right: 20px;
                font-weight: bold;
            }

            img {
                margin-right: 10px;
                height: 100%;
            }
        }
    }
}

</style>