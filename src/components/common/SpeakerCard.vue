<template>
    <div class="card d-flex justify-content-center">
        <div class="d-flex flex-column align-items-center justify-content-center">
            <img :src="require(`@/assets/images/${filename}`)">
            <div><b>{{name}}</b></div>
            <div>{{role}}</div> 
        </div>
    </div>
</template>

<script>
    export default {
        name: 'SpeakerCard',
        data() {
            return {

            }
        },

        props: {
            name: String,
            role: String,
            filename: String,
        }
    }
</script>

<style lang="scss" scoped>

img {
    width: 200px;
    height: 150px;
}
</style>