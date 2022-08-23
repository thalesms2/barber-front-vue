<script setup lang="ts">

</script>

<template>
    <div class="navbar">
        <img src="./../assets/logo.png" alt="logo" class="img-logo">
        <div>
            <a href="#">Agende-se</a>
            <a href="#">Instagram</a>
            <a href="#">Encontre-nos</a>
        </div>
    </div>
</template>

<style scoped>
.navbar {
    background-color: #808080;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
a {
    padding: .5em;
}
.img-logo {
    width: 40px;
    height: 40px;
}
</style>
