<script>
export default {
    data() {
        return {
            imgHero: "../public/img/heroimg.png"
        }
    }
}
</script>

<template>
    <div class="container">
        <img :src="imgHero" alt="">
    </div>
</template>

<style scoped>
.container {
    width: 60%;
    margin: 0 auto;
}

img {
    width: 100%;
    box-shadow: 0px 0px 10px #ffd32b, 0px 2px 10px #ffd32b;
    border-radius: 20px;
    transform: perspective(1500px) rotateY(15deg);
}
</style>