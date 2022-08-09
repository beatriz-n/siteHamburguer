<template>
  <div class="main-container">
    <h1>Gerenciar pedidos:</h1>
    <DashboardComp></DashboardComp>
  </div>
</template>
<script>
import DashboardComp from '@/components/dashboardComp.vue';
export default{
    name: "pedidosView",
    components: { DashboardComp }
}
</script>