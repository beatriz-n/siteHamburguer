<template>
<div>
  <div class="main-container">
    <BannerComp></BannerComp>
    <h1>Monte o seu Burguer:</h1>
        
  </div>
</div>
</template>

<script>
import BannerComp from '@/components/bannerComp.vue';
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
    BannerComp
}
}
</script>
