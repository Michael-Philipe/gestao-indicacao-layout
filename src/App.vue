<template>
  <SideBar />
  <div class="container-fluid" style="padding: 0">
    <Header />
    <main class="container-fluid" style="padding: 0 48px">
      <div class="container-fluid gestao" style="padding: 45px 0 0">
        <div class="title">
          <p>Gestão de indicação</p>
        </div>
        <button>
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <g clip-path="url(#clip0_3215_160)">
              <path
                d="M8.4375 0H11.5625C12.082 0 12.5 0.417969 12.5 0.9375V7.5H15.9258C16.6211 7.5 16.9688 8.33984 16.4766 8.83203L10.5352 14.7773C10.2422 15.0703 9.76172 15.0703 9.46875 14.7773L3.51953 8.83203C3.02734 8.33984 3.375 7.5 4.07031 7.5H7.5V0.9375C7.5 0.417969 7.91797 0 8.4375 0ZM20 14.6875V19.0625C20 19.582 19.582 20 19.0625 20H0.9375C0.417969 20 0 19.582 0 19.0625V14.6875C0 14.168 0.417969 13.75 0.9375 13.75H6.66797L8.58203 15.6641C9.36719 16.4492 10.6328 16.4492 11.418 15.6641L13.332 13.75H19.0625C19.582 13.75 20 14.168 20 14.6875ZM15.1562 18.125C15.1562 17.6953 14.8047 17.3438 14.375 17.3438C13.9453 17.3438 13.5938 17.6953 13.5938 18.125C13.5938 18.5547 13.9453 18.9062 14.375 18.9062C14.8047 18.9062 15.1562 18.5547 15.1562 18.125ZM17.6562 18.125C17.6562 17.6953 17.3047 17.3438 16.875 17.3438C16.4453 17.3438 16.0938 17.6953 16.0938 18.125C16.0938 18.5547 16.4453 18.9062 16.875 18.9062C17.3047 18.9062 17.6562 18.5547 17.6562 18.125Z"
                fill="#ED2B46"
              />
            </g>
            <defs>
              <clipPath id="clip0_3215_160">
                <rect width="20" height="20" fill="white" />
              </clipPath>
            </defs>
          </svg>

          Download Planilha
        </button>
        <button>
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M11.5625 14.9993H8.4375C7.91797 14.9993 7.5 14.5812 7.5 14.0616V7.49817H4.07422C3.37891 7.49817 3.03125 6.6582 3.52344 6.16594L9.46484 0.219759C9.75781 -0.0732529 10.2383 -0.0732529 10.5312 0.219759L16.4766 6.16594C16.9688 6.6582 16.6211 7.49817 15.9258 7.49817H12.5V14.0616C12.5 14.5812 12.082 14.9993 11.5625 14.9993ZM20 14.6867V19.0624C20 19.582 19.582 20 19.0625 20H0.9375C0.417969 20 0 19.582 0 19.0624V14.6867C0 14.1671 0.417969 13.7491 0.9375 13.7491H6.25V14.0616C6.25 15.2688 7.23047 16.2495 8.4375 16.2495H11.5625C12.7695 16.2495 13.75 15.2688 13.75 14.0616V13.7491H19.0625C19.582 13.7491 20 14.1671 20 14.6867ZM15.1562 18.1247C15.1562 17.695 14.8047 17.3434 14.375 17.3434C13.9453 17.3434 13.5938 17.695 13.5938 18.1247C13.5938 18.5545 13.9453 18.9061 14.375 18.9061C14.8047 18.9061 15.1562 18.5545 15.1562 18.1247ZM17.6562 18.1247C17.6562 17.695 17.3047 17.3434 16.875 17.3434C16.4453 17.3434 16.0938 17.695 16.0938 18.1247C16.0938 18.5545 16.4453 18.9061 16.875 18.9061C17.3047 18.9061 17.6562 18.5545 17.6562 18.1247Z"
              fill="#ED2B46"
            />
          </svg>

          Upload Planilha
        </button>
        <button>
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M20 14.6321V6.66063L11.1711 11.2412C11.1513 11.2514 11.1313 11.2611 11.1112 11.2701V19.9996L19.3866 15.5987C19.7668 15.3965 20 15.029 20 14.6321ZM8.60027 11.2416L0 6.77965V14.6325C0 15.0295 0.233188 15.397 0.613373 15.5991L8.88883 20V11.3463C8.78999 11.3243 8.69288 11.2896 8.60027 11.2416Z"
              fill="#ED2B46"
            />
            <path
              opacity="0.3"
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M0.270172 4.61364C0.375222 4.49443 0.507813 4.39369 0.662398 4.3197L9.41234 0.131854C9.77967 -0.0439512 10.2203 -0.0439512 10.5876 0.131854L19.3375 4.3197C19.4567 4.37673 19.5628 4.44967 19.6533 4.5347L10.0599 9.51182C9.99681 9.54455 9.93865 9.58199 9.88565 9.62337C9.83265 9.58199 9.77449 9.54455 9.71141 9.51182L0.270172 4.61364Z"
              fill="#ED2B46"
            />
          </svg>

          Filtro por produto
        </button>
      </div>
      <FilterCar />
      <Table />
    </main>
  </div>
</template>

<script setup>
import SideBar from "./components/SideBar.vue";
import Header from "./components/Header.vue";
import Table from "./components/Table.vue";
import FilterCar from "./components/FilterCar.vue";
</script>

<style>
#app {
  font-family: "Poppins";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background-color: #f3f3f3;
  margin: 0;
  display: flex;
}

main {
  display: flex;
  flex-direction: column;
  gap: 36px;
}

.gestao {
  display: flex;
  padding-top: 43px;
  gap: 20px;
  align-items: center;
  justify-content: space-between;
}

.gestao button {
  display: flex;
  align-items: center;
  height: 46px;
  gap: 20px;
  padding: 10px 15px;
  background-color: #ffffff;
  border-radius: 6px;
  border: none;
  color: #ed2b46;
  min-width: 218px;
}

.title {
  flex: 1;
}

.title p {
  margin: 0;
  font-size: 20px;
  font-weight: 500px;
  color: #464e5f;
}

a {
  padding: 0;
}

p {
  margin: 0;
}
</style>
