<template>
    <div class="bg-black">
        <div class="container">

            --> Content goes here

        </div>
    </div>
</template>

<script>
export default {
    name: 'Content',


}
</script>

<style lang="scss" scoped>

@import '../style/colors';

    .bg-black {
        background-color: black;

        div {
            height: 100px;
            color: $text-color;
            line-height: 100px;
            text-align: left;
        }
    }
</style>