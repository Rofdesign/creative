<template>
    <div class="container">
        <div class="column-text">
            <h1>The space within your walls is full of <br>
            opportunity for individual style</h1>
        </div>
        
        <div class="column-img">
            <img src="~/assets/img/img-2.png" alt="">
        </div>
        <div class="progress">
            <span>
                <h1>1K+</h1>
                <p>Project Finished</p>
            </span>
            <span>
                <h1>124K+</h1>
                <p>Product Sales</p>
            </span>
            <span>
                <h1>1,9K+</h1>
                <p>Total Product</p>
            </span>
            <span>
                <h1>2 Years+</h1>
                <p>Helping People</p>
            </span>
        </div>
    </div>
</template>


<style scoped>
    .container{
        width: 100%;
        text-align: center;
        margin-top: 90px;
        position: relative;
        height: 900px;
    }

    .column-text{
        background: var(--primary-bg);
        color: white;
        height: 450px;
        padding: 70px 0;
    }

    .column-text h1{
        font-size: 45px;
    }

    .column-img{
        width: 100%;
        position: absolute;
        top: 270px;
        height: 500px;
    }

    .column-img img{
        width: 90%;
        height: 500px;
    }

    .progress{
        position: relative;
        display: flex;
        background: #fff;
        width: 80%;
        justify-content: center;
        margin: auto;
        padding: 50px;
        top: 230px;
    }

    .progress span{
        margin: 0 30px;
    }

    .progress span h1{
        color: #ffa500;
        font-size: 35px;
    }
</style>