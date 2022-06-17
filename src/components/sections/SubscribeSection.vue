<template>
    <section class="d-flex justify-content-center align-items-center">
        <div class="my-container d-flex align-items-center flex-column">
            <div class="d-flex justify-content-center">
                <div class="time-block block-1 opacity-75 bg-black d-flex justify-content-center align-items-center flex-column">
                    <div class="number">3399</div>
                    <div>DAYS</div>
                </div>
                <div class="time-block block-2 opacity-50 bg-black d-flex justify-content-center align-items-center flex-column">
                    <div class="number">17</div>
                    <div>HOURS</div>
                </div>
                <div class="time-block block-3 opacity-50 bg-black d-flex justify-content-center align-items-center flex-column">
                    <div class="number">28</div>
                    <div>MINS</div>
                </div>
                <div class="time-block block-4 opacity-50 bg-black d-flex justify-content-center align-items-center flex-column">
                    <div class="number">17</div>
                    <div>SECS</div>
                </div>
            </div>

            <div class="label"><b>SUBSCRIBE FOR UPDATES</b></div>

            <form>
                <input type="text" placeholder="Please fill your email">
                <button class="btn">SUBSCRIBE</button>
            </form>
        </div>
    </section>
</template>

<script>

export default {
    name: 'SubscribeSection',

    data() {
        return {
            
        }
    },

    components: {
    }
}
</script>

<style lang="scss" scoped>

section {
    background-image: url('@/assets/images/coutdown-bg1.jpg');
    height: 400px;
    background-position: center;
}

button {
    background-color: rgb(246, 43, 10);
    color: white;
}

input {
    height: 35px;
    width: 300px;
    margin-right: 10px;
}

.time-block {
    height: 120px;
    margin-right: 20px;
    min-width: 120px;
    color: white;
    font-size: 20px;
    padding: 20px;
}

.number {
    font-size: 50px;
}

.my-container > * {
    margin-bottom: 30px;
}

.label {
    font-size: 25px;
}
</style>