<template>
    <div class="card d-flex flex-column p-2">
        <img :src="require(`@/assets/images/${filename}`)">
        <div class="text-secondary data">{{data}}</div>
        <div><b>{{title}}</b></div>
        <div>{{text}}</div>
        <div><a class="text-danger" href=""><b>Read More</b></a></div>
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
            data: String,
            comments: Number,
        },
    }
</script>

<style lang="scss" scoped>

.card > *{
    margin-bottom: 10px;
}

a {
    font-style: italic;
}

.data {
    font-style: italic;
}
</style>
