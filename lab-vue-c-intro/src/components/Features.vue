<script setup>

    const features = [
        {
            title: "Performant",
            description: "Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.",
            img: "../../src/images/USP-1.png"
        },
        {
            title: "Approachable",
            description: "Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.",
            img: "../../src/images/USP-2.png"
        },
        {
            title: "Versatile",
            description: "A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework.",
            img: "../../src/images/USP-1.png"
        }
    ]

</script>

<template>
    <div class="container">
        <div class="card" v-for="(feature, index) in features" :key="index">
            <img :src=feature.img>
            <h2>{{ feature.title }}</h2>
            <p>{{ feature.description }}</p>
        </div>
    </div>
</template>



<style  scoped>
    div.container{
        width: 100%;
        min-height: 312px;
        background-color: #41b883;
        padding: 1.5rem;
        display: flex;
        justify-content: space-around;
        align-items: flex-start;
    }

    div.card{
        margin-top: 20px;
        max-width: 130px;
        text-align: center;
        color: #000;
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: center;
        gap: 20px;

        h2{
            font-size: 16px;
            font-weight: 800;
        }
        p{
            font-size: 12px;
        }

        img{
            max-width: 60px;
            height: 60px;
            width: 100%;
        }
    }
</style>