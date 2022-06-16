<template>
    <section class="d-flex justify-content-center align-items-center">
        <div class="my-container d-flex flex-column p-2">
            <div class="d-flex justify-content-between">
                <div class="title"><b>PROGRAM</b></div>
                <div class="text">
                    <div>This conference run through all 4 days from 23 - 26 May 2016</div>
                    <div>We also provide free lunch and coffee break in each day</div>
                </div>
                <div>
                    <div class="full">View Full Program</div>
                </div>
            </div>

            <div class="program-box">
                <div class="container">
                    <div class="row first-row">
                        <div class="col active">
                            <div class="day"><b>DAY 1</b></div>
                            <div>23 May 2016</div>
                        </div>
                        <div class="col default">
                            <div class="day"><b>DAY 2</b></div>
                            <div>23 May 2016</div>
                        </div>
                        <div class="col default">
                            <div class="day"><b>DAY 3</b></div>
                            <div>24 May 2016</div>
                        </div>
                        <div class="col default">
                            <div class="day"><b>DAY 4</b></div>
                            <div>25 May 2016</div>
                        </div>
                        <div class="col default">
                            <div class="day"><b>DAY 5</b></div>
                            <div>26 May 2016</div>
                        </div>
                        <div class="col default">
                            
                        </div>
                    </div>
                    <div class="row second-row bg-light">
                        <div class="col-3 col-left">
                            <div>Testo</div>
                            <div>Testo</div>
                            <div>Testo</div>
                        </div>
                        <div class="col col-right">
                            <h4><b>WELCOMING AND INTRODUCTION</b></h4>
                            <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta error dolor cum distinctio laboriosam,</div>
                            <img src="@/assets/images/speaker-8-150x150.jpg" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>

section {
    height: 500px;
}

.title {
    font-size: 30px;
}

.program-box {
    width: 100%;
    height: 300px;
    margin-top: 50px;
}

.row, .col {
    color: white;

}

.first-row > .col {
    border-right: 1px solid black;
    padding: 10px;
}

.active {
    background-color: rgb(199, 43, 17);
}

.default {
    background-color: rgb(246, 43, 10);
}

.day {
    font-size: 18px;
}

.second-row {
    height: 245px;
}

.col-left, .col-right {
    padding: 20px;
    color: gray;
}

h4 {
    color: black;
}

img {
    width: 60px;
    height: 60px;
    margin-top: 20px;
}

.full {
    color: rgb(246, 43, 10);
}
</style>