<script setup>

    const alertComponent = () =>{
        alert("And you are awesome too!")
    }

</script>

<template>
    <div>

        <img alt="Vue logo" class="logo" src="../assets/logo.svg" width="125" height="125" />
        <H1>Welcome to Vue.js</H1>
        <p>Become a coding ninja with the fastest-growing JavaScript framework</p>
        <button @click="alertComponent">Awesome!</button>

    </div>
</template>


<style scoped>
    div{
        margin: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 20px;
        margin-block: 2rem;

        h1{
            font-size: 50px;
            font-weight: 800;
        }
        p{
            max-width: 300px;
            font-size: 14px;
            font-weight: 800;
            text-align: center;
        }

        button{
            background-color: #34495E;
            color: white;
            margin-block: 20px;
            font-weight: 800;
            border: none;
            filter: none;
            width: 120px;
            height: 32px;
            border-radius: 54px;
            transition: all .3s;

            &:hover{
                background-color: #41b883;
            }
        }
    }
</style>