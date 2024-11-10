<script setup>

</script>

<template>
    <div class="wrapper">
        <div class="content">
            <div class="container">
            <h4>our buyers tust us</h4>
            <h2>our goal is to provide our<br>customers with quality product</h2>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Consectetur 
                ipsum porro modi iste provident sint, vero neque nostrum maiores 
                nemo fuga illo excepturi, voluptate quia nobis reprehenderit? 
                Consectetur cum dolore deleniti quasi accusantium ani
                mi! Voluptas pariatur quibusdam illum animi reprehenderit.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing 
                    elit. Nostrum magnam esse voluptates cupiditate
                     tempora quia perspiciatis! Maiores eligendi
                      voluptatibus ducimus, dolorum corrupti
                     exercitationem provident ut laborum \
                     non aliquid veritatis enim.</p>
        </div>
    </div>
        <div class="hr">
            <hr>
            <hr>
        </div>
    </div>
</template>
<style scoped>
.wrapper{
    display: flex;
    align-content: center;
    justify-content: center;
    flex-direction: column;
    text-align: center;
    padding-top: 20px;
}
.content{
    display: grid;
    place-items: center;
    padding-top: 40px;
    text-align: center;
    padding-bottom: 20px;
}
.container{
    width: 500px;
    display: grid;
    place-items: center;
}
p{
    width: 100%;
    padding-bottom: 10px;
}
h4{
    color: tomato;
    text-transform: capitalize;
    padding-bottom: 10px;
    width: 100%;

}
h2{
    text-transform: capitalize;
    font-size: 30px;
    width: 100%;
    padding-bottom: 10px;
}
.hr{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 50px;
}
hr{
    width: 300px;
}
</style>