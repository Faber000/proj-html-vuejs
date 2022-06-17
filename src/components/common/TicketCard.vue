<template>
    <div class="card d-flex flex-column p-2">
        <div class="card-top d-flex flex-column justify-content-center align-items-center p-3">
            <div><h4 class="title">{{title}}</h4></div>
            <div><h4 class="price">{{price}}</h4></div>
        </div>
        <div class="card-center d-flex flex-column justify-content-center align-items-center p-3">
            <div>{{text}}</div>
            <div>Coffee Break</div>
            <div>Lunch</div>
            <div>Document Sheets</div>
            <div>Coffee Break</div>
            <div>100USD Voucher for next event</div>
        </div>
        <div class="card-bottom d-flex flex-column justify-content-center align-items-center p-3">
            <div><b>BOOK NOW</b></div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'AboutUsComponent',
        data() {
            return {

            }
        },

        props: {
            title: String,
            text: String,
            price: String,
        },
    }
</script>

<style lang="scss" scoped>

.card-top {
    background-color: rgb(233, 233, 233);
}

.card-bottom {
    background-color: rgb(243, 46, 10);
    color: white;
}

.card-center {
    background-color: rgb(249, 249, 249);
}

.card-center > * {
    font-style: italic;
}

.card {
    border: none;
}

.title {
    color: black;
}

.price {
    color: rgb(243, 46, 10);
}
</style>
