<template>
    <section>
        <img class="marker" src="@/assets/images/default_marker.png" alt="">
        <img class="google" src="@/assets/images/google4.png" alt="">
        <div class="buttons">
            <button class="btn bg-light border border-light mx-1"><b>Map</b></button>
            <button class="btn bg-light border border-light">Satellite</button>
        </div>
    </section>
</template>

<script>

</script>

<style lang="scss" scoped>

section {
    background-image: url('@/assets/images/maps.jpg');
    height: 400px;
    background-position: center;
    position: relative;
}

.marker {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.google {
    position: absolute;
    bottom: 10px;
    left: 10px;
}

.buttons {
    position: absolute;
    top: 10px;
    left: 10px;
}
</style>
