<template>
    <section class="container-fluid bg-white rounded">
      <div class="container-fluid section">
        <div class="filtro-veiculo">
        <div>
          <svg width="57" height="57" viewBox="0 0 57 57" fill="none" xmlns="http://www.w3.org/2000/svg">
<g clip-path="url(#clip0_1380_352)">
<rect width="57" height="57" fill="#F3F3F3"/>
<path opacity="0.3" d="M43.2961 23.5625H39.7881L38.8131 21.125C37.8111 18.6189 35.4199 17 32.7205 17H25.2791C22.5803 17 20.1885 18.6189 19.1859 21.125L18.2109 23.5625H14.7035C14.2459 23.5625 13.9101 23.9926 14.0215 24.4361L14.373 25.8424C14.451 26.1553 14.7322 26.375 15.0551 26.375H16.231C15.4441 27.0623 14.9373 28.0613 14.9373 29.1875V32C14.9373 32.9446 15.2982 33.7971 15.8748 34.4569V37.625C15.8748 38.6604 16.7144 39.5 17.7498 39.5H19.6248C20.6601 39.5 21.4998 38.6604 21.4998 37.625V35.75H36.4998V37.625C36.4998 38.6604 37.3395 39.5 38.3748 39.5H40.2498C41.2852 39.5 42.1248 38.6604 42.1248 37.625V34.4569C42.7014 33.7977 43.0623 32.9451 43.0623 32V29.1875C43.0623 28.0613 42.5555 27.0623 41.7692 26.375H42.9451C43.268 26.375 43.5492 26.1553 43.6272 25.8424L43.9787 24.4361C44.0895 23.9926 43.7537 23.5625 43.2961 23.5625ZM22.6676 22.5178C23.0947 21.4502 24.1289 20.75 25.2791 20.75H32.7205C33.8707 20.75 34.9049 21.4502 35.332 22.5178L36.4998 25.4375H21.4998L22.6676 22.5178ZM19.6248 31.9883C18.4998 31.9883 17.7498 31.2406 17.7498 30.1192C17.7498 28.9977 18.4998 28.25 19.6248 28.25C20.7498 28.25 22.4373 29.9322 22.4373 31.0537C22.4373 32.1752 20.7498 31.9883 19.6248 31.9883ZM38.3748 31.9883C37.2498 31.9883 35.5623 32.1752 35.5623 31.0537C35.5623 29.9322 37.2498 28.25 38.3748 28.25C39.4998 28.25 40.2498 28.9977 40.2498 30.1192C40.2498 31.2406 39.4998 31.9883 38.3748 31.9883Z" fill="#203972"/>
<path d="M22.6675 22.5178C23.0947 21.4502 24.1289 20.75 25.2791 20.75H32.7205C33.8707 20.75 34.9049 21.4502 35.332 22.5178L36.4998 25.4375H21.4998L22.6675 22.5178ZM19.6248 31.9883C18.4998 31.9883 17.7498 31.2406 17.7498 30.1192C17.7498 28.9977 18.4998 28.25 19.6248 28.25C20.7498 28.25 22.4373 29.9322 22.4373 31.0537C22.4373 32.1752 20.7498 31.9883 19.6248 31.9883ZM38.3748 31.9883C37.2498 31.9883 35.5623 32.1752 35.5623 31.0537C35.5623 29.9322 37.2498 28.25 38.3748 28.25C39.4998 28.25 40.2498 28.9977 40.2498 30.1192C40.2498 31.2406 39.4998 31.9883 38.3748 31.9883Z" fill="#203972"/>
</g>
<defs>
<clipPath id="clip0_1380_352">
<rect width="57" height="57" rx="10" fill="white"/>
</clipPath>
</defs>
</svg>

        </div>
        <div>
          <p>Filtro por veículo</p>
        </div>
      </div>
      <button class="add-button button">
        <svg width="20" height="21" viewBox="0 0 20 21" fill="none" xmlns="http://www.w3.org/2000/svg">
<g clip-path="url(#clip0_3215_895)">
<path d="M18.5714 8.35714H12.1429V1.92857C12.1429 1.13973 11.5031 0.5 10.7143 0.5H9.28571C8.49687 0.5 7.85714 1.13973 7.85714 1.92857V8.35714H1.42857C0.639732 8.35714 0 8.99687 0 9.78571V11.2143C0 12.0031 0.639732 12.6429 1.42857 12.6429H7.85714V19.0714C7.85714 19.8603 8.49687 20.5 9.28571 20.5H10.7143C11.5031 20.5 12.1429 19.8603 12.1429 19.0714V12.6429H18.5714C19.3603 12.6429 20 12.0031 20 11.2143V9.78571C20 8.99687 19.3603 8.35714 18.5714 8.35714Z" fill="#ED2B46"/>
</g>
<defs>
<clipPath id="clip0_3215_895">
<rect width="20" height="20" fill="white" transform="translate(0 0.5)"/>
</clipPath>
</defs>
</svg>


              Adicionar veículo
            </button>
      </div>
      <div class="container-fluid bg-white" style="padding-top: 25px;">
      <form action="">
        <div class="input-container">
          <label for="marca">Marca: <span>*</span></label>
<select id="marca" name="marca">
  <option value="volvo">! Volkswagen</option>
  
</select>
        </div>
        <div class="input-container">
          <label for="marca">Modelo: <span>*</span></label>
<select id="marca" name="marca">
  <option value="volvo">! Fox</option>
  
</select>
        </div>
        <div class="input-container">
          <label for="marca">Versão: <span>*</span></label>
          <input type="text" placeholder="Versão do motor">
        </div>
        
        <div class="input-container input-data">
          <label for="marca">De: <span>*</span></label>
<select id="marca" name="marca">
  <option value="volvo">2019</option>
  
</select>
        </div>
        <div class="input-container input-data">
          <label for="marca">Até: <span>*</span></label>
<select id="marca" name="marca">
  <option value="volvo">2022</option>
  
</select>
        </div>
      </form>
      <div class="container-fluid button-container">
        <button class="button search-button">
          <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
<g clip-path="url(#clip0_3215_201)">
<path d="M19.7266 17.2931L15.832 13.3986C15.6562 13.2228 15.418 13.1251 15.168 13.1251H14.5312C15.6094 11.7462 16.25 10.0118 16.25 8.12512C16.25 3.63684 12.6133 0.00012207 8.125 0.00012207C3.63672 0.00012207 0 3.63684 0 8.12512C0 12.6134 3.63672 16.2501 8.125 16.2501C10.0117 16.2501 11.7461 15.6095 13.125 14.5314V15.1681C13.125 15.4181 13.2227 15.6564 13.3984 15.8322L17.293 19.7267C17.6602 20.0939 18.2539 20.0939 18.6172 19.7267L19.7227 18.6212C20.0898 18.254 20.0898 17.6603 19.7266 17.2931ZM8.125 13.1251C5.36328 13.1251 3.125 10.8907 3.125 8.12512C3.125 5.3634 5.35938 3.12512 8.125 3.12512C10.8867 3.12512 13.125 5.3595 13.125 8.12512C13.125 10.8868 10.8906 13.1251 8.125 13.1251Z" fill="white"/>
</g>
<defs>
<clipPath id="clip0_3215_201">
<rect width="20" height="20" fill="white"/>
</clipPath>
</defs>
</svg>



              Pesquisar por veículo
            </button>
      </div>
    </div>
    </section>
    
</template>
  
  <script>
  export default {
    name: 'FilterCar',
  };
  </script>
  
  <script setup></script>
  
  <style scoped>

 
  .filtro-veiculo {
    display: flex;
    flex-direction: row;
    align-items: center;
    height: 57px;
  }
  .filtro-veiculo p {
    margin: 0;
    font-weight: 600;
  }

  .section {
    padding: 20px;
    display: flex;
    justify-content: space-between;
    border-bottom: 0.5px solid #B5B5C3;
  }

  .rounded {
    border-radius: 6px;
  }
 

  .button{
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 10px 15px;
  gap: 20px;
  width: 219px;
  height: 46px;
  
  border-radius: 6px;
  font-weight: 500;
  font-size: 17px;
  /* line-height: 26px; */

  
  border: none;
  cursor: pointer;
  }

  .add-button {
    color: #ed2b46;
    background-color: rgba(237, 43, 70, 0.1);
  }

  .search-button {
    background-color: #ED2B46;
    color: #ffffff;
    width: 253px;
    font-size: 17px;
   
  }

  .button-container{
    padding: 0;
    display: flex;
    justify-content: flex-end;
    padding: 20px 0;
    
  }

  .input-container {
    display: flex;
    flex-direction: column;
    width: 401px;
    flex: auto;
  }

  .input-container input {
    height: 100%;
    border-radius: 6px;
    color: #B5B5C3;
    padding-left: 20px;
  }

  label {
    font-weight: 600;
    font-size: 17px;
    color: #464e5f;
    height: 26px;
  }
  .input-data{
    min-width: 40%;
  }

 
  .input-data label {
    font-size: 14px;
  }

  .input-data select {
    text-align: center;
  }
  label span {
    color: #F64E60;
  }
  select {
    height: 45px;
    padding: 0 20px;


  }

  form {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    gap: 25px;
  }

  /* select::before {
  content: "\f13a";
  font-family: FontAwesome;
  position: absolute;
  top: 0;
  right: 0;
  width: 20%;
  height: 100%;
  text-align: center;
  font-size: 28px;
  line-height: 45px;
  color: rgba(255, 255, 255, 0.5);
  background-color: rgba(112, 55, 165, 0.5);
  pointer-events: none;
} */
 
  
  </style>
  