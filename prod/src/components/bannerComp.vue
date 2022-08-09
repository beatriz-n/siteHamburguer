<template>
<div>
    <div id="main-banner"></div>
</div>
    
</template>

<script>
export default{
 name:'bannerComp'
}
</script>

<style scoped>
#main-banner{
    background-image:url('C:\Users\Usuario\Downloads\github\siteHamburguer\prod\public\img\burger.jpg');
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}
#main-banner h1{
    color: aliceblue;
    text-align: center;
    font-size: 60px;
    background-color: black;

    }
</style>