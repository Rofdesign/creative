<template>
    <div class="container">
        <div class="column-text">
            <h1>Great Innovation<br>Starts Here</h1>
            <div class="para">
                <p>Do i have consent to record this meeting gain traction,<br>
                    root-and-branch review, nor game-plan who's</p>
                <br>
                <span class="btn-1">Contact us</span>
                <span class="btn-2">Our Portfolio</span>
            </div>
        </div>
        <div class="footer-links">
            <img src="~/assets/img/logo.png" alt="">
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">Services</a></li>
                <li><a href="">Blog</a></li>
                <li><a href="">About</a></li>
            </ul>

            <p>Copyright 2022 - rofdesigns</p>
        </div>
    </div>
</template>


<style scoped>
    .container{
        background: var(--primary-bg);
        width: 100%;
        padding: 5% 10%;
        
    }

    .column-text{
        display: flex;
        justify-content: space-between;
        border-bottom: 1px solid #fff;
        padding-bottom: 50px;
    }

    .column-text h1{
        font-size: 50px;
        color: #fff;
    }

    .column-text .para p{
        margin: 20px 0;
        color: #fff;
    }

    .column-text .para span{
        margin-right: 20px;
    }

    .footer-links{
        text-align: center;
        margin-top: 50px;
        color: #fff;
    }

    .footer-links img{
        width: 20%;
    }

    .footer-links ul{
        list-style: none;
        display: flex;
        justify-content: center;
        margin: 20px 0;
    }

    .footer-links ul li{
        margin: 0 25px;
    }

    .footer-links ul li a{
        color: #fff;
        text-decoration: none;
        font-size: 18px;
    }

</style>