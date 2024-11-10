<script setup>

</script>

<template>
    <div class="wrapper">
        <h2>subscripe to our news letter</h2>
        <div class="input-field">
            <div class="input">
                <input type="email" placeholder="e-mail">
            </div>
            <div class="btn">
                <button type="submit">submit</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.wrapper{
    width: 100%;
    text-align: center;
    text-transform: capitalize;
    padding-top: 60px;
    padding-bottom: 60px;
}
.input-field{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 40px;
    padding-block: 30px;
}
.input{
    height: 40px;
    width: 208px;
}
input{
    width: 100%;
    height: 100%;
    padding-inline: 10px;
}
.btn{
    width: 100px;
    height: 40px;
    cursor: pointer;
    
}
button{
    width: 100%;
    height: 100%;
    background: tomato;
    text-transform: capitalize;
    outline: none;
    border: none;
    border-radius: 5px;
    color: snow;
}
</style>