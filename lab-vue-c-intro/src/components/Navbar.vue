<script setup>
console.log("navBar")
</script>

<template>
    <header>
        <img src="../images/Ironhack_logo.png" alt="ironHack Logo">
        <img class="burger" src="../images/Burger_menu.png" alt="ironHack Logo">
    </header>
</template>

<style scoped>
header{
    display: flex;
    justify-content: space-between;
    width: 100%;
    min-height: 80px;
    align-items: center;
    padding-inline: 1rem;

    & img{
        max-width: 35px;
        width: 100%;
    }

    .burger{
        max-width: 20px;
    }
}
</style>