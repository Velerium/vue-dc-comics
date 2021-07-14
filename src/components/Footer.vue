<template>
    <div class="bg-image">
        <div class="container">
            <div class="links">
                <div>

                    <ul>
                        <li>DC COMICS</li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>

                    <ul>
                        <li>SHOP</li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>

                </div>

                <ul>
                    <li>DC</li>
                    <li>Terms Of Use</li>
                    <li>Privacy Policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>

                <ul>
                    <li>SITES</li>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>

            </div>

            <div class="bg-logo">
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer',


}
</script>

<style lang="scss" scoped>

@import '../style/colors';
@import '../style/fonts';

.bg-image {
    background-image: url('../assets/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    align-items: center;
    height: 350px;

    .container {
        justify-content: space-between;
    
        .links {
            display: flex;
            padding: 25px 0;

            ul {
                text-align: left;
                margin-right: 30px;

                li {
                    list-style: none;
                    color: #888;
                    margin-bottom: 5px;
                    font-size: $font-small;

                    &:first-child {
                        color: $text-color;
                        font-size: 22px;
                        font-weight: bold;
                        margin: 18px 0;
                    }
                }
                
            }
        }
    

        .bg-logo {
            background-image: url('../assets/dc-logo-bg.png');
            width: 50%;
            height: 350px;
            background-position-y: center;
            background-repeat: no-repeat;
        }
    }
}





</style>