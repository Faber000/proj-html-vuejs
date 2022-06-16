<template>
    <main>
        <AboutUsSection/>
        <SubscribeSection/>
        <SpeakerSection/>
        <ProgramSection/>
    </main>
</template>


<script>

import AboutUsSection from '@/components/sections/AboutUsSection.vue'
import SubscribeSection from '@/components/sections/SubscribeSection.vue'
import SpeakerSection from '@/components/sections/SpeakerSection.vue'
import ProgramSection from '@/components/sections/ProgramSection.vue'


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
        ProgramSection,
    }
}
</script>


<style lang="scss" scoped>

</style>