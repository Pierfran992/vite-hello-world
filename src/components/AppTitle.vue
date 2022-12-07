<script>
export default {
    data() {
        return {
            title1: "La mia prima ",
            title2: "app con Vite!"
        }
    }
}
</script>

<template>
    <h1>
        <span class="title1">{{ title1 }}</span>
        <span class="title2">{{ title2 }}</span>
    </h1>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');

h1 {
    font-family: 'Pacifico', cursive;

}

.title1 {
    color: #9961fe;
}

.title2 {
    color: #41b883;
}
</style>