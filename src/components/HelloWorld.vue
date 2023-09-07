<template>
    <div class="about">
      <div id="mainText">COMAP HiMCM <br> & MidMCM <br> @ DCSG 2023</div>
      <img src="src\assets\calculator.jpg">
    </div>

</template>
  
<style>
@font-face {
    font-family: PoppinsBold;
    src: url("../assets/Poppins-Bold.ttf");
}
@font-face {
    font-family: Poppins;
    src: url("../assets/Poppins-Regular.ttf");
}
*{
    margin: 0;
    padding: 0;
}
.about{
    background-color: white;
    height: 430px;
    display: block;
}
img{
    max-height: 350px;
    width: 350px;
    object-fit: cover;
    border-radius: 500px;
    position: absolute;
    right: 100px;
    margin-top: 40px;
}

#mainText{
    color: rgb(239, 51, 64);
    font-size: 70px;
    font-weight: bold;
    font-family: PoppinsBold;
    margin-top: 50px;
    margin-left: 50px;
    position: absolute;
}
@media screen and (max-width: 1024px) {
    img{
        visibility: hidden;
    }
    #mainText{
        font-size: 50px;
    }
}
</style>
  