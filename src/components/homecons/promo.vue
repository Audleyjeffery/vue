<script setup>
import img1 from '@/assets/img/dinning.jpg'
</script>

<template>
    <div class="wrapper">
        <h1>-promo sellers-</h1>
        <div class="container">
            <div class="container_items">
                <div class="product">
                    <img :src="img1" alt="">
                </div>
                <div class="content">
                    <div class="price">
                        <h3>best dinning set</h3>
                        <p class="amount">N3,000</p>
                    </div>
                    <div class="order">
                        <h3 class="ord">order</h3>
                    </div>
                </div>
            </div>
            <div class="container_items">
                <div class="product">
                    <img :src="img1" alt="">
                </div>
                <div class="content">
                    <div class="price">
                        <h3>best dinning set</h3>
                        <p class="amount">N3,000</p>
                    </div>
                    <div class="order">
                        <h3 class="ord">order</h3>
                    </div>
                </div>
            </div>
            <div class="container_items">
                <div class="product">
                    <img :src="img1" alt="">
                </div>
                <div class="content">
                    <div class="price">
                        <h3>best dinning set</h3>
                        <p class="amount">N3,000</p>
                    </div>
                    <div class="order">
                        <h3 class="ord">order</h3>
                    </div>
                </div>
            </div>
            <div class="container_items">
                <div class="product">
                    <img :src="img1" alt="">
                </div>
                <div class="content">
                    <div class="price">
                        <h3>best dinning set</h3>
                        <p class="amount">N3,000</p>
                    </div>
                    <div class="order">
                        <h3 class="ord">order</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
.wrapper{
    width: 100%;
}
.wrapper h1{
    text-align: center;
    text-transform: capitalize;
    font-size: 50px;
    padding-block: 20px;
    font-weight: 300;
}
.container{
    widows: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 20px;
}
.container_items{
    width: 350px;
    height: 350px;
    border: 2px solid snow;
    border-radius: 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    box-shadow: 0 6px 6px rgba(0,0,0,0.5);
}
.product{
    width: 300px;
    height: 300px;
    overflow: hidden;
    border: 2px solid snow;
    border-radius: 10px;
    padding-top: 10px;
}
.product img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 10px;
}
.content{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 300px;
    padding-block: 10px;
    text-transform: capitalize;
}
.order{
    background: tomato;
    padding: 10px 20px 10px 20px;
    color: snow;
}
</style>