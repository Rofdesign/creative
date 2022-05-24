<template>
    <div class="container">
        <div class="slider">
            <img src="~/assets/img/latest.png" alt="">
        </div>
        <div class="column-text">
            <h1>Natural <br>
            inspiration in<br>
            every room</h1>
            <p>Do i have consent to record this meeting gain traction,<br>
            root-and-branch review, nor game-plan who's</p>
            <span class="btn-1">Search Now</span>
            <span class="btn-2">See our Portfolio</span>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .container{
        width: 100%;
        display: flex;
        margin: 40px 0;
    }

    .slider{
        margin-right: 50px;
    }

    .column-text{
        padding: 30px 0;
    }

    .column-text h1{
        font-size: 43px;
        font-weight: 800;
        margin: 20px 0;
    }

    .column-text p{
        margin: 20px 0;
        margin-bottom: 50px;
    }

    .column-text span{
        margin-right: 20px;
        border: 1px solid grey;
        padding: 10px 20px;
        font-weight: 500;
    }

    .column-text .btn-1{
        background: orange;
        border: none;
    }

    .column-text .btn-2{
        color: green;
    }
</style>