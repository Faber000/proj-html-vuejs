<template>
    <section>
        <div class="my-container container my-5">
            <div class="d-flex justify-content-between align-items-center mb-3">
                <div>
                    <h3 class="text-dark">RECENT NEWS</h3>
                </div>
                <div>
                    <div class="all-news"><b>Read All News</b></div>
                </div>   
            </div>
            <div class="row">
                <div class="col-4">
                    <NewsCard title="COME SE FOSSE" :text="text" filename="photodune-7770665-two-white-coffee-mug-with-diy-decoration-o (2).jpg" data="03 Dec 2016" comments="0"/>
                </div>
                <div class="col-4">
                    <NewsCard title="SBIRIGUDA" :text="text" filename="photodune-8797753-multiethnic-people-with-startup-business-t (2).jpg" data="03 Dec 2016" comments="2"/>
                </div>
                <div class="col-4">
                    <NewsCard title="ANTANI" :text="text" filename="photodune-8523683-speaker-at-business-convention-and-present (1).jpg" data="03 Dec 2016" comments="2"/>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import NewsCard from '../common/NewsCard.vue'

export default {
    name: 'NewsSection',
    data() {
        return {
            text: "Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet",
        }
    },

    components: {
        NewsCard,
    }
}
</script>

<style lang="scss" scoped>


.all-news {
    color: rgb(246, 43, 10);
    font-style: italic;
}
</style>
