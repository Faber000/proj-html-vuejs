<template>
    <div>
        <div class="hero-div d-flex justify-content-center align-items-center" :style="{'background-image': 'url(' + require(`@/assets/images/${filename}`) + ')'}" alt="">
            <div class="my-container d-flex justify-content-center align-items-center flex-column">
                <h2>CONFERENCE ON</h2>
                <h1 class="title">SOCIAL NETWORKS</h1>
                <img src="@/assets/images/1-item-2.jpg" alt="">    
                <small>23 - 26 maggio 2019 / San Francisco / 8 Speaker</small>      
                <button class="btn register-btn p-2">REGISTER ONLINE</button>      
            </div>
        </div>
    </div>
</template>

<script>

export default {
    name: 'BaseHero',
    data() {
        return {

        }
    },

    props: {
        filename: String,
    }

}
</script>

<style lang="scss" scoped>

.hero-div {
    height: 500px;
}

.my-container > * {
    margin-bottom: 20px;
}

.register-btn {
    background-color: rgb(246, 43, 10);
    color: white;
}

.title {
    font-size: 50px;
}

small {
    color: white;
}
</style>
