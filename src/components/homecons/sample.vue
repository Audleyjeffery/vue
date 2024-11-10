<script setup>
import img1 from '@/assets/img/IMG-20210424-WA0022.jpg'
import img2 from '@/assets/img/dinning.jpg'
import img3 from '@/assets/img/tri.jpg'
</script>
<template>
<div class="wrapper">
    <div class="content">
        <h1>samples</h1>
        <h3>check out this cool sample</h3>
        <p>get a glimpse of some of our best product to keep your desires avlive</p>
    </div>
    <div class="samples">
            <div class="sample">
                <img :src="img1" alt="">
                <div class="overlay">
                    <h1 class="card-title">living room</h1>
                    <h3 class="title2">
                        observe the best shit man
                    </h3>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quaerat est,
                     magnam nemo eum distinctio dolor consequuntur alias fugiat autem id!</p>
                </div>
            </div>
            <div class="sample">
                <img :src="img2" alt="">
                <div class="overlay">
                    <h1 class="card-title">living room</h1>
                    <h3 class="title2">
                        observe the best shit man
                    </h3>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quaerat est,
                     magnam nemo eum distinctio dolor consequuntur alias fugiat autem id!</p>
                </div>
            </div>
            <div class="sample">
                <img :src="img3" alt="">
                <div class="overlay">
                    <h1 class="card-title">living room</h1>
                    <h3 class="title2">
                        observe the best shit man
                    </h3>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quaerat est,
                     magnam nemo eum distinctio dolor consequuntur alias fugiat autem id!</p>
                </div>
            </div>
        </div>
</div>
</template>

<style scoped>
.wrapper{
    width: 100%;
}
.wrapper .content{
    text-transform: capitalize;
    text-align: center;
    /* padding: 20px 10px 20px 10px; */
}

.samples{
    display: flex;
    justify-content: space-around;
    align-items: center;
    position: relative;
}
.sample{
    width: 400px;
    height: 350px;
    overflow: hidden;
    border-radius: 20px;
    position: relative;
}
.sample img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 20px;
}
.overlay{
    height: 100%;
    width: 100%;
    background: rgba(0, 0, 0, 0.418);
    top: 0;
    right: -100%;
    position: absolute;
    color: snow;
    border-radius: 20px;
    display: grid;
    place-items: center;
    padding-top: 100px;
    text-transform: capitalize;
    transition: 0.5s;
    backdrop-filter: blur(5px);
}
/* .card-title{
    padding-bottom: 10px;
} */
.sample:hover .overlay{
    right: 0;
}
/* p{
    padding: 0 30px 0 30px;
} */

</style>