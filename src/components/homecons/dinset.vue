<script setup>
import img1 from '@/assets/img/dinning.jpg'
</script>

<template>
    <div class="wrapper">
        <div class="content">
            <h4>dinning set</h4>
            <h2><span>best</span> dinning set</h2>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                 Deserunt aliquam itaque ipsam voluptatibus, illum laborum
                  assumenda neque, quis eveniet aliquid culpa delectus reprehenderit
                 velit voluptates id, laboriosam iusto animi tenetur?</p>
                 <div class="btn">
                    <h3>dinning set view</h3>
                 </div>
        </div>
        <div class="dinning_img">
            <img :src="img1" alt="">
        </div>
    </div>
</template>
<style scoped>
.wrapper{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding-top: 50px;
}
.content{
    width: 400px;
    text-transform: capitalize;
}
h4{
    padding-bottom: 10px;
    font-size: 20px;
}
h2{
    padding: 0 0 20px 0;
    font-size: 50px;
}
span{
    color: tomato;
}
.btn{
    background: tomato;
    padding: 10px 20px 10px 20px;
    width: 180px;
    height: 50px;
    margin-top: 10px;
    color: snow;
}
.dinning_img{
    width: 600px;
    height: 300px;
    border-radius: 20px;
    border: 2px solid black;
    overflow: hidden;
}
.dinning_img img{
    width: 100%;
    height: 100%;
    border: 20px;
}

</style>