<template>
    <section class="d-flex justify-content-center align-items-center">
        <div class="my-container d-flex">
            <AboutUsComponent :title="'WHO WE ARE'" :text="text" filename="speaker-3.jpg"/>
            <AboutUsComponent :title="'WHAT WE DO'" :text="text" filename="speaker-3.jpg"/>
            <AboutUsComponent :title="'WHY US?'" :text="text" filename="speaker-3.jpg"/>
        </div> 
    </section>
</template>

<script>
import AboutUsComponent from '../common/AboutUsComponent.vue'

export default {
    name: 'AboutUsSection',

    data() {
        return {
            text: "Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet"
        }
    },

    components: {
        AboutUsComponent,
    }
}
</script>

<style lang="scss" scoped>

section {
    height: 200px;
}
</style>
