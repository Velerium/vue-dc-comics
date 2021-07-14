<template>
    <div class="container menu">

        <div class="logo">
            <img src="../assets/dc-logo.png" alt="">
        </div>
        <nav>
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>

    </div>
</template>

<script>
export default {
    name: 'Header',


}
</script>

<style lang="scss" scoped>

@import '../style/fonts';
    .menu {
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;

        .logo {
             
            img {
                width: 70%;
            }
        }

        ul {
            display: flex;

            li {
                list-style: none;
                margin-left: 15px;
                font-size: $font-small;
                font-weight: bold;
            }
        }
    }

</style>