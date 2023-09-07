<script setup lang="ts">
import appRouter from '@/router'
function pushPre(){
    appRouter.push('/prerequisites');
}
</script>
<template>
    <div class="header">
      <div class="texts">
        DCSG COMAP 2023
      </div>
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
.header{
    background-color: rgb(239, 51, 64);
    height: 60px;
    display: block;
}
.texts{
    color: white;
    font-family: PoppinsBold;
    font-size: 30px;
    position: absolute;
    margin-top: 7px;
    margin-left: 50px;
}
.lists{
    color: white;
    font-family: PoppinsBold;
    font-size: 30px;
    position: absolute;
    margin-top: 7px;
    right: 30px;
    text-align: end;
}

</style>
  