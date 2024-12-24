<template>
    <div class="container text-center">
        <h1 class="text-primary">Привет, Bootstrap!</h1>
        <button class="btn btn-success">Кнопка Bootstrap</button>
    </div>
</template>

<script>
export default {
    name: "HelloWorld",
    data() {
        return {
            message: "Привет, Nuxt 222!"
        };
    }
};
</script>

<style scoped>
body {
    margin: 0;
    padding: 0;
}
h1 {
    color: #2c3e50;
}
</style>