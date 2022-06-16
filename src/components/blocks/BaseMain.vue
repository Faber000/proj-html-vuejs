<template>
    <main>
        <AboutUsSection/>
        <SubscribeSection/>
        <SpeakerSection/>
    </main>
</template>


<script>

import AboutUsSection from '@/components/sections/AboutUsSections.vue'
import SubscribeSection from '@/components/sections/SubscribeSection.vue'
import SpeakerSection from '@/components/sections/SpeakerSection.vue'


export default {
    name: 'BaseMain',
    data() {
        return {

        }
    },

    components: {
        AboutUsSection,
        SubscribeSection,
        SpeakerSection,
    }
}
</script>


<style lang="scss" scoped>

</style>