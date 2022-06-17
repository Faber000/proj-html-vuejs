<template>
    <section class="d-flex justify-content-center align-items-center">
        <div class="my-container d-flex justify-content-center align-items-center flex-column">
                <h1>LOCATION</h1>
                <h3>GD BUILDIND, GRAND CONFERENCE ROOM</h3>
                <small>11 GD Building, River Mall, New York, USA 8879</small>
                <small class="text-danger">Check for Accomodations here</small>   
                <img src="@/assets/images/1-item-2.jpg" alt=""> 
                <div class="d-flex contacts">
                    <div class="mx-5">
                        +1-117-222-3344
                    </div>
                    <div>
                        Contact@TheKeynodeTheme.com
                    </div>
                </div>     
            </div>
    </section>
</template>

<script>

export default {
    name: 'LocationSection',
    data() {
        return {

        }
    },

}
</script>

<style lang="scss" scoped>

.my-container > * {
    margin-bottom: 20px;
}

section {
    height: 400px;
    background-image: url('@/assets/images/location-bg.jpg');
}

small, .contacts {
    color: white;
}

</style>