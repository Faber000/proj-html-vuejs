<template>
    <div class="component d-flex justify-content-center">
        <div class="d-flex align-items-start">
            <font-awesome-icon :icon="icon" />
        </div>

        <div class="d-flex flex-column">
            <div><h5 class="text-dark">{{title}}</h5></div>
            <div>{{text}}</div>
            <div class="my-4"><a href=""><b>Learn More</b></a></div>
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
            icon: String,
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
    font-style: italic;
}


</style>
