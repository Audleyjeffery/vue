<script setup>
</script>
<template>
    <div id="hero">
            <div class="content slide_top">
                <span><h1>interior paradise</h1></span>
                <h3>live your interior dreams here</h3>
                <p>we at interior paradise</p>
            </div>
        </div>
</template>
<style scoped>
#hero{
    background-image:url('@/assets/bgim.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    height: 50vh;
}
.content{
    padding: 50px 100px 50px 100px;
    text-transform: capitalize;
    opacity: 0;
    transform: translateY(60px);

}

.slide_top{
    animation: slidertop 0.5s ease-in 1s forwards;
}

@keyframes slidertop{
    from{
        transform: translateY(60px);
        opacity: 0;
    }

    to{
        transform: translateY(0);
        opacity: 1;
    }
}
</style>