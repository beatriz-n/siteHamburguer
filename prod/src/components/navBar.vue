<template>
    <div id="nav">
<router-link to="/" id="logo-url">
    <img :src="logoSrc" :alt="alt" id="logo">
</router-link>

<router-link to="/">Home</router-link>
<router-link to="/pedidosView">About</router-link>
    </div>
</template>

<script>
export default{
 name: 'navBar',
 props: ["logoScr", "alt"]
}
</script>

<style scoped>
#nav{
  background-color: black;
  border-bottom: 4px solid black;
  padding: 15px 50px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
#nav #logo-url{
margin: auto;
margin: 0;
}
#logo{
    width: 40px;
    height: 40px;
}
#nav a{
    color: rgb(255, 208, 66);
    text-decoration: none;
    margin: 12px;
    transition: .5s;
}
#nav a:hover{
    color: aliceblue;
}
</style>