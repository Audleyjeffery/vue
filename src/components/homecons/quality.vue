<script setup>
import img1 from '@/assets/img/dinning.jpg'
</script>

<template>
    <div class="wrapper">
        <div class="content">
            <img :src="img" alt="">
            <div class="info">
                <h3>fast delivery</h3>
                <p>Lorem ipsum dolor sit amet
                     consectetur adipisicing elit. 
                     Suscipit consequatur quaerat 
                     consectetur asperiores quis 
                     vero officiis nihil, earum 
                     magnam error impedit quia corporis optio nemo s
                     unt tenetur ullam ex incidunt ducimus hic sit cumque! Harum voluptates ipsa
                     laboriosam.<br> Quisquam suscipit modi amet vo
                     luptatibus, beatae libero asperiores vel cumque hic reprehenderit?</p>
            </div>
        </div>
        <div class="content">
            <img :src="img" alt="">
            <div class="info">
                <h3>fast delivery</h3>
                <p>Lorem ipsum dolor sit amet
                     consectetur adipisicing elit. 
                     Suscipit consequatur quaerat 
                     consectetur asperiores quis 
                     vero officiis nihil, earum 
                     magnam error impedit quia corporis optio nemo s
                     unt tenetur ullam ex incidunt ducimus hic sit cumque! Harum voluptates ipsa
                     laboriosam.<br> Quisquam suscipit modi amet vo
                     luptatibus, beatae libero asperiores vel cumque hic reprehenderit?</p>
            </div>
        </div>
        <div class="content">
            <img :src="img" alt="">
            <div class="info">
                <h3>fast delivery</h3>
                <p>Lorem ipsum dolor sit amet
                     consectetur adipisicing elit. 
                     magnam error impedit quia corporis optio nemo s
                     unt tenetur ullam ex incidunt ducimus hic sit cumque! Harum voluptates ipsa
                     laboriosam.<br> Quisquam suscipit modi amet vo
                     luptatibus, beatae libero asperiores vel cumque hic reprehenderit?</p>
            </div>
        </div>
    </div>
</template>

<style scoped>
.wrapper{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding-top: 80px;
}
.content{
    text-align: center;
}
p{
    padding: 10px 100px 10px 100px;
}
.content img{
    width: 60px;
    height: 60px;
    object-fit: cover;
}
</style>