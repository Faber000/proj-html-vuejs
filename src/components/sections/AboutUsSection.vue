<template>
    <section class="d-flex justify-content-center align-items-center">
        <div class="my-container container d-flex justify-content-center align-items-center">
            <div class="row">
                <div class="col-4">
                    <AboutUsComponent title="WHO WE ARE" :text="text" icon="trophy"/>
                </div>
                <div class="col-4">
                    <AboutUsComponent title="WHAT WE DO" :text="text" icon="bolt"/>
                </div>
                <div class="col-4">
                    <AboutUsComponent title="WHY US" :text="text" icon="question"/>
                </div>
            </div>
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
    height: 300px;
}
</style>
