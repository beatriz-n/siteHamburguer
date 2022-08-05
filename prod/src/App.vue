<template>
  <div>
  <NavBar :logo="logoSrc" :alt="appName"></NavBar>
  <router-view/>
  <FooterComp></FooterComp>
  </div>
</template>
<script>
import NavBar from './components/navBar.vue';
import FooterComp from './components/footerComp.vue';
export default{
  components: {
    NavBar, 
    FooterComp 
},
  data() {
    return {
      logoSrc: 'https://github.com/matheusbattisti/curso_vue_yt/blob/main/18_projeto/public/img/logo.png?raw=true',
      appName: 'Faça seu Burguer'
      }
  }

}
</script>
<style scoped>

*{
  font-family: Arial, Helvetica, sans-serif;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.main-container{
  margin: 50px;
  min-height: 250px;
}
h1{
  align-items: center;
  justify-content: center;
  font-size: 42px;
  margin-bottom: 30px;
  color: rgb(22, 22, 22);
}
</style>
