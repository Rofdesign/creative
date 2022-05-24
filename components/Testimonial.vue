<template>
    <div class="container">
        <div class="column-text">
            <h1>Every room<br>deserves to<br>be amazing</h1>
            <p>Do i have consent to record this meeting<br>gain traction,
            root-and-branch review, nor<br>game-plan who's</p>
        </div>

        <div class="comment-container">
            <div class="comment-box">
                <p class="comment-text">" We're building the plane while we're flying it big data yet<br>
                drop-dead date. Due diligence teams were able to drive<br>
                and awareness currying "</p>
                <div class="comment-user">
                    <h2>John Alexander</h2> <p>Florinda, USA</p>
                </div>
            </div>
            <div class="comment-box">
                <p class="comment-text">" We're building the plane while we're flying it big data yet<br>
                drop-dead date. Due diligence teams were able to drive<br>
                and awareness currying "</p>
                <div class="comment-user">
                    <h2>John Alexander</h2> <p>Florinda, USA</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .container{
        width: 85%;
        display: flex;
        margin: 30px 0;
    }

    .column-text{
        width: 40%;
        padding: 50px;
    }

    .column-text h1{
        font-size: 50px;
        margin-bottom: 30px;
    }

    .comment-container{
        width: 57%;
    }

    .comment-box{
        border: 1px solid orange;
        padding: 40px;
        margin: 15px 0;
    }

    .comment-box .comment-text{
        margin: 15px 0;
    }

    .comment-box .comment-user{
        display: flex;
        color: orange;
    }

    .comment-box .comment-user p{
        padding: 6px;
    }

    .comment-box h2{
       color: #000;
       padding: 0;
       margin-right: 10px;
    }
</style>