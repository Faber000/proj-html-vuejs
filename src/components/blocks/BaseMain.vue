<template>
    <main>
        <AboutUsSection/>
        <SubscribeSection/>
        <SpeakerSection/>
        <ProgramSection/>
        <MapsSection/>
        <LocationSection/>
        <NewsSection/>
        <TicketSection/>
        <TwitterSection/>
        <SponsorsSection/>
    </main>
</template>


<script>

import AboutUsSection from '@/components/sections/AboutUsSection.vue'
import SubscribeSection from '@/components/sections/SubscribeSection.vue'
import SpeakerSection from '@/components/sections/SpeakerSection.vue'
import ProgramSection from '@/components/sections/ProgramSection.vue'
import MapsSection from '@/components/sections/MapsSection.vue'
import LocationSection from '@/components/sections/LocationSection.vue'
import NewsSection from '@/components/sections/NewsSection.vue'
import TicketSection from '@/components/sections/TicketSection.vue'
import TwitterSection from '@/components/sections/TwitterSection.vue'
import SponsorsSection from '@/components/sections/SponsorsSection.vue'



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
        MapsSection,
        LocationSection,
        NewsSection,
        TicketSection,
        TwitterSection,
        SponsorsSection,
    }
}
</script>


<style lang="scss" scoped>

</style>