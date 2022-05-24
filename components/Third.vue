<template>
    <div class="container">
        <div class="column-text">
            <h1>We don't design Interiors,<br>
                We design Feelings!
            </h1>
            <p>Do i have consent to record this meeting gain traction,<br>
            root-and-branch review, nor game-plan who's</p>
            <div class="highlights">
                <span>Flexible time</span>
                <span>Community Support</span>
                <span>Globally recognised</span>
                <span>Afforable cost</span>
            </div>
            <span class="btn-1">Discover More</span>
        </div>

        <div class="column-img">
            <img src="~/assets/img/img-1.png" alt="">
        </div>
    </div>
</template>

<style scoped>
    .container{
        width: 100%;
        display: flex;
    }

    .column-text{
        width: 60%;
        padding: 40px;
    }

    .column-text h1{
        font-size: 45px;
        font-weight: 800;
    }

    .column-text p{
        margin: 35px 0;
    }

    .highlights{
       display: grid;
       grid-template-columns: repeat(2,1fr);
       margin-bottom: 40px;
    }

    .highlights span{
       font-size: 18px;
       font-weight: 600;
       margin: 10px 0;
    }

    .column-img{
        width: 40%;
    }

    .column-img img{
        width: 100%;
    }
</style>