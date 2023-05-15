<template>
  <SideBar />
  <div class="container-fluid" style="padding: 0">
    <Header />
    <main class="container-fluid" style="padding: 0 48px;">
      <FilterCar/>

      <Table/>
    </main>
  </div>
</template>

<script setup>
import SideBar from './components/SideBar.vue';
import Header from './components/Header.vue';
import Table from './components/Table.vue';
import FilterCar from './components/FilterCar.vue'
</script>

<style>
#app {
  font-family: 'Poppins';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background-color: #f3f3f3;
  height: 100%;
  margin: 0;
  display: flex;
}

main {
  display: flex;
  flex-direction: column;
  gap: 36px ;
}

a {
  padding: 0;
}

p{
  margin: 0;
}
</style>
