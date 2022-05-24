

<template>    
        <div class="nav-container" id="nav-container">

            <div class="logo"><img src="~/assets/img/logo.png" alt=""></div>
            <div class="links">
                <ul>
                    <li><NuxtLink to="/">Home</NuxtLink></li>  
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Project</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </div>
            <span class="btn-1">Explore</span>
        </div>
</template>



<style scoped>
    #nav-container{
        height: 80px;
        width: 100%;
        padding: 15px 150px;
        display: flex;
        justify-content: space-between;
    }

    .nav-container span{
        padding: 10px 30px;
    }
    
    .logo{
    }

    .logo img{
        width: 170px;
        height: 70px;
    }

    .links ul{
        display: flex;
        list-style: none;
        font-size: 15px;
    }

    .links ul li{
        padding: 10px 30px;
    }

    .links ul li a{
        text-decoration: none;
        color: #d7d7d7;
        display: inline-block;
        position: relative;
        font-size: 17px;
    }

    .links ul li a:after{
        content: '';
        position: absolute;
        width: 100%;
        transform: scaleX(0);
        border-radius: 3px;
        height: 3px;
        bottom: -3px;
        left: 0;
        background-color: orange;
        transform-origin: bottom center;
        transition: transform 0.25s ease-out;
    }

    .links ul li a:hover:after {
        transform: scaleX(1);
        transform-origin: bottom center;
    }

</style>