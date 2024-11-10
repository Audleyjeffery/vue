<script setup>


</script>

<template>
    <div class="wrapper">
        <div class="content">
            <div class="home">
                <img src="" alt="">
                <h3>home</h3>
            </div>
            <div class="watchlist">
                <img src="" alt="">
                <h3>watchlist</h3>
                <div class="added"></div>
            </div>
            <div class="my account">
                <img src="" alt="">
                <h3>my account</h3>
            </div>
            <div class="cart">
                <img src="" alt="">
                <h3>cart</h3>
                <div class="added"></div>
            </div>
        </div>
    </div>
</template>
<style scoped>
.wrapper{
    width: 100%;
    position: relative;
}
.content{
    align-items: center;
    justify-content: space-between;
    display: flex;
    padding-inline: 30px;
    text-transform: capitalize;
    background: black;
    width: 100%;
    position: fixed;
    padding-block: 10px;
    bottom: 0;
    color: snow;
}
</style>