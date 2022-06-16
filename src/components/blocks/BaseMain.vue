<template>
    <main>
        <AboutUsSection/>
    </main>
</template>


<script>

import AboutUsSection from '@/components/sections/AboutUsSections.vue'

export default {
    name: 'BaseMain',
    data() {
        return {

        }
    },

    components: {
        AboutUsSection,
    }
}
</script>


<style lang="scss" scoped>

</style>