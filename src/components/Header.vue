<template>
  <header class="container-fluid">
    <nav class="container-fluid navbar bg-white">
      <div class="logo">
        <p>Nome da loja</p>
      </div>
      <div class="user">
        <div class="info">
          <p>Nickolas G.</p>
          <p>Administrador</p>
        </div>
        <div class="logo">
          <svg width="38" height="38" viewBox="0 0 38 38" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect width="38" height="38" rx="19" fill="#E72F48"/>
<path d="M19.1252 18.0301C16.7013 18.0301 14.7363 16.0565 14.7363 13.6219C14.7363 11.1873 16.7013 9.21362 19.1252 9.21362C21.5492 9.21362 23.5142 11.1873 23.5142 13.6219C23.5142 16.0565 21.5492 18.0301 19.1252 18.0301Z" fill="white"/>
<path d="M9.25078 28.1681C9.67607 22.9083 13.9263 20.2341 19.1068 20.2341C24.3601 20.2341 28.6763 22.7614 28.9978 28.1689C29.0106 28.3844 28.9978 29.0506 28.1735 29.0506C24.1077 29.0506 18.0659 29.0506 10.0483 29.0506C9.77312 29.0506 9.22761 28.4546 9.25078 28.1681Z" fill="white"/>
</svg>
 
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComponent',
};
</script>

<script setup></script>

<style scoped>
header {
  padding: 0 50px 0 50px;
  height: 70px;
  background-color: #ffffff;
  box-shadow: 0px 4px 5px rgba(0, 0, 0, 0.07);
}

.navbar {
  height: inherit;
}



.logo{
  font-size: 20px;
  display: flex;
  align-items: center;
  font-weight: 500;
  color: #464E5F;
}

.logo p {
  margin: 0;
  
}
.user {
  display: flex;
  flex-direction: row;
  width: 130px;
  height: 30px;
  /* justify-content: space-around; */
  gap: 20px;

}

.info p{
  margin: 0;
}

.info p:first-child{
  font-size: 13px;
}

.info p {
  font-size: 10px;
}
</style>
