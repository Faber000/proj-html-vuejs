<template>
    <section class="d-flex justify-content-center align-items-center">
        <div class="my-container container my-5">
            <div class="d-flex justify-content-center mb-3 align-items-center">
                <div>
                    <h1>TICKETS</h1>
                </div>  
            </div>
            <div class="row">
                <div class="col-4">
                    <TicketCard title="ONE DAY PASS" text="One Day Access" price="FREE"/>
                </div>
                <div class="col-4">
                    <TicketCard title="FOUR DAY PASSES" text="Four day Access" price="750.000 USD"/>
                </div>
                <div class="col-4">
                    <TicketCard title="TWO DAY PASSES" text="Two day Access" price="580.000 USD"/>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import TicketCard from '../common/TicketCard.vue'

export default {
    name: 'TicketSection',
    data() {
        return {
            
        }
    },

    components: {
        TicketCard,
    }
}
</script>

<style lang="scss" scoped>

section {
    background-image: url("@/assets/images/ticket-bg.jpg");
    height: 500px;
}
</style>
