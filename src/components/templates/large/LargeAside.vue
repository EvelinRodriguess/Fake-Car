<!-- LargeAside.vue -->
<script setup>
import LogoTitle from '@/components/templates/LogoTitle.vue';
</script>
<template>
  <div class="logo_and_menu">
    <logo-title class="mb-2" />
    <div class="divider" />
    <div class="menu">
      <router-link to="/">
        <i class="icon mdi mdi-home-outline" /> Home
      </router-link>
    </div>
    <div class="divider" />
    <div class="menu">
      <router-link to="/login">
        <i class="icon mdi mdi-login" /> Login
      </router-link>
      <router-link to="/acessorios">
        <i class="icon mdi mdi-car-parking-lights" /> Acessórios
      </router-link>
      <router-link to="/categoria">
        <i class="icon mdi mdi-car-back" /> Categorias
      </router-link>
      <router-link to="/cor">
        <i class="icon mdi mdi-format-color-fill" /> Cores
      </router-link>
      <router-link to="/marca">
        <i class="icon mdi mdi-car-convertible" /> Marcas
      </router-link>
      
    </div>
  </div>
  <logo-title />
</template>
<style scoped>
.mb-2 {
  margin-bottom: 1.5rem;
}

.icon {
  font-size: 2rem;
  align-self: center;
}

.divider {
  margin-top: 1rem;
  border-top: 1px solid rgb(255, 255, 255);
}

.menu {
  padding: 2rem;
}

.menu a {
  display: flex;
  align-items: center;
  text-decoration: none;
  color: #000000;
  gap: 1rem;
  font-size: 1.3rem;
  margin-top: 2.2rem;
}
</style>
  
 