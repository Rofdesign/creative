<template>
    <div class="container">
        <img src="~/assets/img/untitled-1.png" alt="">
        <div class="column-container">

            <div class="column-text">
                <h1>Create a home<br>
                that defines <br>
                who you are</h1>

                <p>Do i have consent to record this meeting gain<br> traction,
                root-and-branch review, nor game-<br>plan who's the goto</p>
                <br>
                <span class="btn-1">Get Started</span>
                <span class="btn-2">See Our Portfolio</span>
            </div>

            <div class="column-img">
                <div class="img-1">
                    <img src="~/assets/img/img-1.png" alt="">
                </div>

                <div class="img-grid">
                    <div class="img-2">
                        <img src="~/assets/img/img-2.png" alt="">
                    </div>
                    <div class="img-2">
                        <img src="~/assets/img/latest.png" alt="">
                    </div>
                </div>
            </div>
            
        </div>
        
    </div>
</template>

<style scoped>
   .container{
       width: 100%;
       height: 900px;
   }
   .container img{
       width: 100%;
   }

   .container img{
       width: 100%;
      position: absolute;
   }

   .column-container{
       position: relative;
       display: flex;
   }

   .column-text{
       padding: 50px 100px;
       margin: 0 40px;
       width: 50%;
   }

   .column-text h1{
       font-size: 60px;
       color: #fff;
   }

   .column-text p{
       font-size: 20px;
       color: #dadada;
       margin: 20px 0;
   }

   .column-text span{
       margin-right: 20px;
   }

   .column-img{

       width: 50%;
       display: block;
       
   }

   .column-img .img-1{
       
       width: 100%;
       height: 550px;
       margin-bottom: 15px;
   }

   .column-img .img-1 img{
       width: 710px;
       height: 550px;
   }

   .column-img .img-grid{
       
       width: 100%;
       height: 200px;
       display: flex;
       grid-gap: 20px;
   }

   .column-img .img-2{
       width: 48%;
       height: 200px; 
   }

   .column-img .img-2 img{
       width: 350px;
       height: 200px;

   }


</style>