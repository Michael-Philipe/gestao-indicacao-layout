<template>
  <div
    class="d-flex flex-column flex-shrink-0 "
    style="width: 80px; background-color: #143266; height: 2024px;"
  >
    <a
      href="/"
      class="d-block p-0 link-dark text-decoration-none logo"
      title="Icon-only"
      data-bs-toggle="tooltip"
      data-bs-placement="right"
    >
      <img :src="logo" alt="" srcset="" />
      <span class="visually-hidden">Icon-only</span>
    </a>
    <ul class="nav nav-pills nav-flush flex-column mb-auto text-center">
      <li class="nav-item">
        <a
          href="#"
          class="nav-link py-3"
          aria-current="page"
          title="Home"
          data-bs-toggle="tooltip"
          data-bs-placement="right"
        >
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <g clip-path="url(#clip0_3186_491)">
              <path
                opacity="0.3"
                d="M19.4041 11.1765H10.6802L16.4902 16.9864C16.7122 17.2085 17.0777 17.2265 17.306 17.0114C18.7288 15.671 19.7074 13.864 19.9946 11.8327C20.0438 11.4849 19.7552 11.1765 19.4041 11.1765ZM18.8221 8.79412C18.5192 4.40221 15.0096 0.892649 10.6177 0.589708C10.2824 0.566547 10.0001 0.849267 10.0001 1.1853V9.41177H18.2269C18.5629 9.41177 18.8453 9.12941 18.8221 8.79412ZM8.23537 11.1765V2.45258C8.23537 2.10147 7.92692 1.81287 7.57949 1.86213C3.19824 2.48125 -0.150655 6.30883 0.00522741 10.896C0.165522 15.607 4.22177 19.4702 8.93501 19.411C10.7879 19.3879 12.5001 18.7908 13.9078 17.7923C14.1982 17.5864 14.2174 17.1588 13.9655 16.907L8.23537 11.1765Z"
                fill="white"
              />
              <path
                d="M18.8221 8.79412C18.5192 4.40221 15.0096 0.892649 10.6177 0.589708C10.2824 0.566547 10.0001 0.849267 10.0001 1.1853V9.41177H18.2269C18.5629 9.41177 18.8453 9.12941 18.8221 8.79412Z"
                fill="white"
              />
            </g>
            <defs>
              <clipPath id="clip0_3186_491">
                <rect width="20" height="20" fill="white" />
              </clipPath>
            </defs>
          </svg>
        </a>
      </li>
      <li>
        <a
          href="#"
          class="nav-link py-3"
          title="Dashboard"
          data-bs-toggle="tooltip"
          data-bs-placement="right"
        >
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              opacity="0.3"
              d="M10.0001 14H4.00011V9H2.00011V17C2.00011 17.5531 2.44698 18 3.00011 18H11.0001C11.5532 18 12.0001 17.5531 12.0001 17V9H10.0001V14ZM19.8314 6.44375L17.1657 2.44375C16.9782 2.16563 16.6657 2 16.3314 2H3.66886C3.33448 2 3.02198 2.16563 2.83761 2.44375L0.171984 6.44375C-0.271766 7.10938 0.203234 8 1.00323 8H19.0001C19.797 8 20.272 7.10938 19.8314 6.44375ZM16.0001 17.5C16.0001 17.775 16.2251 18 16.5001 18H17.5001C17.7751 18 18.0001 17.775 18.0001 17.5V9H16.0001V17.5Z"
              fill="white"
            />
            <path
              d="M19.8312 6.44375L17.1656 2.44375C16.9781 2.16563 16.6656 2 16.3312 2H3.66874C3.33436 2 3.02186 2.16563 2.83749 2.44375L0.171862 6.44375C-0.271888 7.10938 0.203112 8 1.00311 8H19C19.7969 8 20.2719 7.10938 19.8312 6.44375Z"
              fill="white"
            />
          </svg>
        </a>
      </li>
      <li>
        <a
          href="#"
          class="nav-link py-3"
          title="Orders"
          data-bs-toggle="tooltip"
          data-bs-placement="right"
        >
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <g clip-path="url(#clip0_3186_501)">
              <path
                d="M19.0391 12.332L17.375 11.3711C17.543 10.4648 17.543 9.53516 17.375 8.62891L19.0391 7.66797C19.2305 7.5586 19.3164 7.33204 19.2539 7.1211C18.8203 5.73047 18.082 4.47266 17.1172 3.42579C16.9687 3.26563 16.7266 3.22657 16.5391 3.33594L14.875 4.29688C14.1758 3.69532 13.3711 3.23047 12.5 2.92579V1.00782C12.5 0.789068 12.3477 0.597662 12.1328 0.550787C10.6992 0.230475 9.23046 0.2461 7.86718 0.550787C7.65234 0.597662 7.5 0.789068 7.5 1.00782V2.92969C6.63281 3.23829 5.82812 3.70313 5.12499 4.30079L3.46484 3.33985C3.27343 3.23047 3.03515 3.26563 2.88671 3.42969C1.92187 4.47266 1.18359 5.73047 0.749995 7.12501C0.683589 7.33594 0.773432 7.56251 0.964839 7.67188L2.6289 8.63282C2.46093 9.53907 2.46093 10.4688 2.6289 11.375L0.964839 12.3359C0.773432 12.4453 0.687495 12.6719 0.749995 12.8828C1.18359 14.2734 1.92187 15.5313 2.88671 16.5781C3.03515 16.7383 3.27734 16.7773 3.46484 16.668L5.1289 15.707C5.82812 16.3086 6.63281 16.7734 7.5039 17.0781V19C7.5039 19.2188 7.65625 19.4102 7.87109 19.457C9.30468 19.7773 10.7734 19.7617 12.1367 19.457C12.3516 19.4102 12.5039 19.2188 12.5039 19V17.0781C13.3711 16.7695 14.1758 16.3047 14.8789 15.707L16.543 16.668C16.7344 16.7773 16.9727 16.7422 17.1211 16.5781C18.0859 15.5352 18.8242 14.2773 19.2578 12.8828C19.3164 12.668 19.2305 12.4414 19.0391 12.332ZM10 13.125C8.27734 13.125 6.875 11.7227 6.875 10C6.875 8.27735 8.27734 6.87501 10 6.87501C11.7227 6.87501 13.125 8.27735 13.125 10C13.125 11.7227 11.7227 13.125 10 13.125Z"
                fill="white"
              />
            </g>
            <defs>
              <clipPath id="clip0_3186_501">
                <rect width="20" height="20" fill="white" />
              </clipPath>
            </defs>
          </svg>
        </a>
      </li>
      <li>
        <a
          href="#"
          class="nav-link py-3"
          title="Products"
          data-bs-toggle="tooltip"
          data-bs-placement="right"
        >
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
              d="M20 14.6321V6.66064L11.1711 11.2412C11.1513 11.2514 11.1313 11.2611 11.1112 11.2701V19.9996L19.3866 15.5987C19.7668 15.3966 20 15.0291 20 14.6321ZM8.60027 11.2416L0 6.77966V14.6325C0 15.0295 0.233188 15.397 0.613373 15.5991L8.88883 20V11.3464C8.78999 11.3243 8.69288 11.2896 8.60027 11.2416Z"
              fill="white"
            />
            <path
              opacity="0.3"
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M0.270142 4.61364C0.375191 4.49443 0.507782 4.39369 0.662367 4.3197L9.41231 0.131854C9.77963 -0.0439512 10.2202 -0.0439512 10.5876 0.131854L19.3375 4.3197C19.4567 4.37673 19.5628 4.44967 19.6532 4.5347L10.0599 9.51182C9.99678 9.54455 9.93862 9.58199 9.88562 9.62337C9.83261 9.58199 9.77446 9.54455 9.71138 9.51182L0.270142 4.61364Z"
              fill="white"
            />
          </svg>
        </a>
      </li>
      <li>
        <a
          href="#"
          class="nav-link py-3"
          title="Customers"
          data-bs-toggle="tooltip"
          data-bs-placement="right"
        >
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              opacity="0.3"
              d="M17.6246 6.44443H15.7537L15.2337 4.7111C14.6993 2.92902 13.424 1.77777 11.9843 1.77777H8.01552C6.57614 1.77777 5.30052 2.92902 4.76583 4.7111L4.24583 6.44443H2.3752C2.13114 6.44443 1.95207 6.75027 2.01145 7.06568L2.19895 8.06568C2.24051 8.28818 2.39051 8.44443 2.5627 8.44443H3.18989C2.7702 8.93318 2.49989 9.64359 2.49989 10.4444V12.4444C2.49989 13.1161 2.69239 13.7223 2.99989 14.1915V16.4444C2.99989 17.1807 3.4477 17.7778 3.99989 17.7778H4.99989C5.55208 17.7778 5.99989 17.1807 5.99989 16.4444V15.1111H13.9999V16.4444C13.9999 17.1807 14.4477 17.7778 14.9999 17.7778H15.9999C16.5521 17.7778 16.9999 17.1807 16.9999 16.4444V14.1915C17.3074 13.7228 17.4999 13.1165 17.4999 12.4444V10.4444C17.4999 9.64359 17.2296 8.93318 16.8102 8.44443H17.4374C17.6096 8.44443 17.7596 8.28818 17.8012 8.06568L17.9887 7.06568C18.0477 6.75027 17.8687 6.44443 17.6246 6.44443ZM6.6227 5.70152C6.85052 4.94235 7.40208 4.44443 8.01552 4.44443H11.9843C12.5977 4.44443 13.1493 4.94235 13.3771 5.70152L13.9999 7.77776H5.99989L6.6227 5.70152ZM4.99989 12.4361C4.39989 12.4361 3.99989 11.9044 3.99989 11.1069C3.99989 10.3094 4.39989 9.77776 4.99989 9.77776C5.59989 9.77776 6.49989 10.974 6.49989 11.7715C6.49989 12.569 5.59989 12.4361 4.99989 12.4361ZM14.9999 12.4361C14.3999 12.4361 13.4999 12.569 13.4999 11.7715C13.4999 10.974 14.3999 9.77776 14.9999 9.77776C15.5999 9.77776 15.9999 10.3094 15.9999 11.1069C15.9999 11.9044 15.5999 12.4361 14.9999 12.4361Z"
              fill="white"
            />
            <path
              d="M6.62281 5.70151C6.85063 4.94235 7.40219 4.44443 8.01563 4.44443H11.9844C12.5978 4.44443 13.1494 4.94235 13.3772 5.70151L14 7.77777H6L6.62281 5.70151ZM5 12.4361C4.4 12.4361 4 11.9044 4 11.1069C4 10.3094 4.4 9.77777 5 9.77777C5.6 9.77777 6.5 10.974 6.5 11.7715C6.5 12.569 5.6 12.4361 5 12.4361ZM15 12.4361C14.4 12.4361 13.5 12.569 13.5 11.7715C13.5 10.974 14.4 9.77777 15 9.77777C15.6 9.77777 16 10.3094 16 11.1069C16 11.9044 15.6 12.4361 15 12.4361Z"
              fill="white"
            />
          </svg>
        </a>
      </li>
      <li>
        <a
          href="#"
          class="nav-link py-3"
          title="Customers"
          data-bs-toggle="tooltip"
          data-bs-placement="right"
        >
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <g clip-path="url(#clip0_3186_517)">
              <path
                d="M19.6285 12.5035C19.2188 12.132 18.5799 12.1563 18.1493 12.5035L14.941 15.0695C14.5486 15.3854 14.059 15.5556 13.5521 15.5556H9.44444C9.13889 15.5556 8.88889 15.3056 8.88889 15C8.88889 14.6945 9.13889 14.4445 9.44444 14.4445H12.1632C12.7153 14.4445 13.2292 14.066 13.3194 13.5208C13.434 12.8264 12.8993 12.2222 12.2222 12.2222H6.66667C5.72917 12.2222 4.82292 12.5451 4.09375 13.1354L2.47917 14.4445H0.555556C0.25 14.4445 0 14.6945 0 15V18.3333C0 18.6389 0.25 18.8889 0.555556 18.8889H12.9444C13.4479 18.8889 13.9375 18.7188 14.3333 18.4028L19.5833 14.2014C20.1111 13.7813 20.1528 12.9757 19.6285 12.5035Z"
                fill="white"
              />
              <path
                opacity="0.3"
                d="M9.55902 9.80902C9.80207 10.066 10.1979 10.066 10.4444 9.80902L14.2257 5.84374C15.3229 4.69096 15.2604 2.78124 14.0312 1.71874C12.9618 0.791655 11.368 0.958322 10.3889 1.9861L9.99999 2.39235L9.61457 1.98957C8.63541 0.958322 7.04166 0.791655 5.97221 1.71874C4.74652 2.78124 4.68055 4.69096 5.77777 5.84374L9.55902 9.80902Z"
                fill="white"
              />
            </g>
            <defs>
              <clipPath id="clip0_3186_517">
                <rect width="20" height="20" fill="white" />
              </clipPath>
            </defs>
          </svg>
        </a>
      </li>
    </ul>
  
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<script setup>
import logo from "../assets/logo2.png";
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-item {
  height: 50px;
  width: 100%;
  /* background-color: #143266; */
}
.logo {
  text-align: center;
}
</style>
