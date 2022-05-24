<template>
    <div class="container">
        <ul>
            <li><a href="">Bedroom</a></li>
            <li><a href="">Dining Room</a></li>
            <li><a href="">Kitchen</a></li>
            <li><a href="">Home Office</a></li>
            <li><a href="">Living Room</a></li>
        </ul>
    </div>
</template>

<style scoped>
    .container{
        width: 80%;
    }

    .container ul{
        width: 100%;
        display: grid;
        grid-template-columns: repeat(3,1fr);
        padding: 0;
    }

    .container ul li{
        height: 50px;
        list-style: none;
        padding: 10px 30px;
        text-align: center;
        margin: 10px 0;
        transition: all 0.4s ease-in-out;
    }

    .container ul li:not(:nth-of-type(3)){
        border-right: 3px solid black;
    }

    .container ul li:hover{
        background: #007AFF;
        color: #fff;
    }

    .container ul li a{
       text-decoration: none;
       color: black;
       
    }
</style>