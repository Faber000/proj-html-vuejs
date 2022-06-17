<template>
    <header>
        <div class="my-container m-auto">
            <nav class="navbar bg-white p-2">
                <img src="@/assets/images/logo.png" alt="">
                <a class="navbar-link" v-for="(link,index) in navLinks" :key="index" href="#"><b>{{link}}</b></a>
            </nav>
        </div>
        <BaseHero :filename="filename"/>
    </header>
</template>

<script>
import BaseHero from '../common/BaseHero.vue'

export default {
    data() {
        return {
            filename: "slider-1-bg.jpg",
            navLinks: ['HOME', 'PAGES', 'PROGRAM', 'TICKETS', 'SPEAKERS','PAPERS', 'BLOG'],
        }
    },
    components: {
        BaseHero,
    }
}
</script>

<style lang="scss" scoped>

.navbar-link {
    color: gray;
}

.navbar {
    height: 50px;
}

</style>