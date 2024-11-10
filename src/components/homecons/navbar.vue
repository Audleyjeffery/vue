<script setup>

</script>

<template>
    <div class="nav">
        <img src="" alt="" class="logo">
        <div class="links slide_right">
            <a href="">Home</a>
            <a href="">About</a>
            <a href="">Product</a>
            <a href="">Services</a>
            <a href="">Contact</a>
        </div>
    </div>
</template>

<style scoped>
.links a{
    text-decoration: none;
    font-size: 20px;
    padding-inline: 20px;
    font-weight: 300;
    text-transform: capitalize;
    color: black;
   
}
.links{
    transform: translateX(40px);
    opacity: 0;
}
 .slide_right{
    animation :slideright 0.5s ease 1s forwards;
 }
@keyframes slideright{
    from{
        transform: translateX(40px);
        opacity: 0;
    }
    to{
        transform: translateX(0);
        opacity: 1;
    }
}
.nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-inline: 40px;
    padding-block: 20px;
    background-color: whitesmoke;
    color: bisque;
}


</style>