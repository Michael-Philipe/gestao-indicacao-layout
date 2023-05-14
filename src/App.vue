<template>
  <SideBar />
  <div class="container-fluid" style="padding: 0">
    <Header />
    <Table />
  </div>
</template>

<script setup>
import SideBar from './components/SideBar.vue';
import Header from './components/Header.vue';
import Table from './components/Table.vue';
</script>

<style>
#app {
  font-family: 'Poppins';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #f3f3f3;
  margin-top: 60px;
  height: 100%;
  margin: 0;
  max-width: 1500px;
  display: flex;
}
a {
  padding: 0;
}
</style>
