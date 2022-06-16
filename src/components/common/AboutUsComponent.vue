<template>
    <div class="component d-flex justify-content-center">
        <div class="d-flex align-items-start">
             <img :src="require(`@/assets/images/${filename}`)">
        </div>

        <div class="d-flex flex-column">
            <div>{{title}}</div>
            <div>{{text}}</div>
            <div><a href="">Learn More</a></div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'AboutUsComponent',
        data() {
            return {

            }
        },

        props: {
            title: String,
            text: String,
            filename: String,
        }
    }
</script>

<style lang="scss" scoped>

img {
    width: 80px;
    height: 50px;
}

.component > * {
    margin-right: 10px;
}

a {
    color: rgb(246, 43, 10);
}
</style>
