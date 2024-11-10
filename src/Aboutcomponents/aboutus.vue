<script setup>
import img2 from '@/assets/img/dinning.jpg'
</script>

<template>
    <div class="wrappper">
        <div class="content">
            <img :src="img2" alt="">
            <h2>we are interior bla bla blah</h2>
        </div>
    </div>
</template>

<style scoped>
.wrapper{
    width: 100%;
}

.content{
    width: 100%;
    height: 60vh;
}
.content img{
    width: 100%;
    height: 100%;
    object-fit: cover;
}
</style>