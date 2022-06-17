<template>
    <section class="d-flex justify-content-center align-items-center">
        <div class="my-container d-flex flex-column p-3">
            <div class="section-top d-flex justify-content-between mb-3">
                <h3 class="text-dark">PRESENTATION</h3>
                <h3 class="text-dark">TWITTER FEED</h3>
            </div>
            <div class="section-bottom d-flex">
                <div class="section-left mx-5">
                    <img src="@/assets/images/461365506_640.jpg" alt="">
                </div>
                <div class="section-right d-flex flex-column">
                    <div class="d-flex my-3">
                        <img class="twitter-logo" src="@/assets/images/twitter.png" alt="">
                        <div><small>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam earum temporibus accusantium aut </small></div>
                    </div>
                    <div class="d-flex my-3">
                        <img class="twitter-logo" src="@/assets/images/twitter.png" alt="">
                        <div><small>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam earum temporibus accusantium aut </small></div>
                    </div>
                    <div class="d-flex my-3">
                        <img class="twitter-logo" src="@/assets/images/twitter.png" alt="">
                        <div><small>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam earum temporibus accusantium aut </small></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>

</script>

<style lang="scss" scoped>

.twitter-logo {
    width: 30px;
    height: 30px;
}

.section-left > img {
    width: 500px;
    height: 300px;
}

section {
    height: 500px;
}

.section-top {
    width: 850px;
}

.my-container {
    width: 1200px;
}

</style>