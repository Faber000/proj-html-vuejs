<template>
    <section class="d-flex justify-content-center align-items-center bg-light">
        <div class="my-container d-flex flex-column">
            <div class="d-flex justify-content-between">
                <div class="title"><b>SPEAKERS</b></div>
                <div class="d-flex">
                    <button class="mx-2"></button>
                    <button></button>
                </div>
            </div>
            <div class="cards d-flex justify-content-between">
                <SpeakerCard :name="'PATRICK SPENCER'" :role="'S&P Analyzer'" filename="speaker-2.jpg"/>
                <SpeakerCard :name="'JANET JONES'" :role="'Newyork Post GM'" filename="speaker-5.jpg"/>
                <SpeakerCard :name="'MICHAEL DOVER'" :role="'Starbucks CEO'" filename="speaker-4.jpg"/>
                <SpeakerCard :name="'ANGELINA HOLY'" :role="'Maxii Manager'" filename="speaker-3.jpg"/>
            </div>
        </div>
    </section>
</template>

<script>
import SpeakerCard from '../common/SpeakerCard.vue'

export default {
    name: 'SpeakerSection',
    data() {
        return {

        }
    },

    components: {
        SpeakerCard,
    }
}
</script>

<style lang="scss" scoped>
button {
    width: 40px;
    height: 40px;
    background-color: rgb(246, 43, 10);
    border: none;
}

.title {
    font-size: 30px;
}

.my-container {
    padding: 20px;
}

.my-container > * {
    margin-bottom: 20px;
}
</style>