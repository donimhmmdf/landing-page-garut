<template>
  <header class="w-full h-screen py-6 px-4 flex flex-col">
    <nav class="container z-10">
      <div class="flex justify-between items-center">
        <div
          class="text-white hover:text-blue-500 transition duration-300 ease-in-out font-bold text-xl"
        >
          <a href="#">Indonesia</a>
        </div>
        <div
          class="bg-transparent hover:bg-blue-500 text-white font-semibold hover:text-white py-2 px-4 border border-white hover:border-transparent rounded-lg"
        >
          <a href="#">Sign Up</a>
        </div>
      </div>
    </nav>
    <div class="m-auto text-white text-7xl font-semibold z-10">Garut.</div>
    <div class="header-bottom flex justify-between container z-10">
      <div class="text-white text-3xl">
        {{ tanggal }} <span class="text-xl">/ {{ bulan }}</span>
      </div>
      <ul class="flex items-center">
        <li>
          <a
            href=""
            class="w-9 h-9 mr-3 rounded-full flex justify-between items-center text-white hover:text-blue-500 transition duration-300 ease-in-out hover:shadow-md"
          >
            <svg
              role="img"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="30"
              class="fill-current"
            >
              <title>GitHub</title>
              <path
                d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
              />
            </svg>
          </a>
        </li>
        <li>
          <a
            href=""
            class="w-9 h-9 mr-3 rounded-full flex justify-between items-center text-white hover:text-blue-500 transition duration-300 ease-in-out hover:shadow-md"
          >
            <svg
              role="img"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="35"
              class="fill-current"
            >
              <title>Upwork</title>
              <path
                d="M18.561 13.158c-1.102 0-2.135-.467-3.074-1.227l.228-1.076.008-.042c.207-1.143.849-3.06 2.839-3.06 1.492 0 2.703 1.212 2.703 2.703-.001 1.489-1.212 2.702-2.704 2.702zm0-8.14c-2.539 0-4.51 1.649-5.31 4.366-1.22-1.834-2.148-4.036-2.687-5.892H7.828v7.112c-.002 1.406-1.141 2.546-2.547 2.548-1.405-.002-2.543-1.143-2.545-2.548V3.492H0v7.112c0 2.914 2.37 5.303 5.281 5.303 2.913 0 5.283-2.389 5.283-5.303v-1.19c.529 1.107 1.182 2.229 1.974 3.221l-1.673 7.873h2.797l1.213-5.71c1.063.679 2.285 1.109 3.686 1.109 3 0 5.439-2.452 5.439-5.45 0-3-2.439-5.439-5.439-5.439z"
              />
            </svg>
          </a>
        </li>
        <li>
          <a
            href=""
            class="w-9 h-9 mr-3 rounded-full flex justify-between items-center text-white hover:text-blue-500 transition duration-300 ease-in-out hover:shadow-md"
            ><svg
              class="fill-current"
              role="img"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="35"
            >
              <title>Flickr</title>
              <path
                d="M5.334 6.666C2.3884 6.666 0 9.055 0 12c0 2.9456 2.3884 5.334 5.334 5.334 2.9456 0 5.332-2.3884 5.332-5.334 0-2.945-2.3864-5.334-5.332-5.334zm13.332 0c-2.9456 0-5.332 2.389-5.332 5.334 0 2.9456 2.3864 5.334 5.332 5.334C21.6116 17.334 24 14.9456 24 12c0-2.945-2.3884-5.334-5.334-5.334Z"
              />
            </svg>
          </a>
        </li>
        <li>
          <a
            href=""
            class="w-9 h-9 mr-3 rounded-full flex justify-between items-center text-white hover:text-blue-500 transition duration-300 ease-in-out hover:shadow-md"
          >
            <svg
              role="img"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="35"
              class="fill-current"
            >
              <title>Fiverr</title>
              <path
                d="M23.004 15.588a.995.995 0 1 0 .002-1.99.995.995 0 0 0-.002 1.99zm-.996-3.705h-.85c-.546 0-.84.41-.84 1.092v2.466h-1.61v-3.558h-.684c-.547 0-.84.41-.84 1.092v2.466h-1.61v-4.874h1.61v.74c.264-.574.626-.74 1.163-.74h1.972v.74c.264-.574.625-.74 1.162-.74h.527v1.316zm-6.786 1.501h-3.359c.088.546.43.858 1.006.858.43 0 .732-.175.83-.487l1.425.4c-.351.848-1.22 1.364-2.255 1.364-1.748 0-2.549-1.355-2.549-2.515 0-1.14.703-2.505 2.45-2.505 1.856 0 2.471 1.384 2.471 2.408 0 .224-.01.37-.02.477zm-1.562-.945c-.04-.42-.342-.81-.889-.81-.508 0-.81.225-.908.81h1.797zM7.508 15.44h1.416l1.767-4.874h-1.62l-.86 2.837-.878-2.837H5.72l1.787 4.874zm-6.6 0H2.51v-3.558h1.524v3.558h1.591v-4.874H2.51v-.302c0-.332.235-.536.606-.536h.918V8.412H2.85c-1.162 0-1.943.712-1.943 1.755v.4H0v1.316h.908v3.558z"
              />
            </svg>
          </a>
        </li>
        <!-- <li>
          <a href="">Flickr</a>
        </li>
        <li>
          <a href="">Upwork</a>
        </li>
        <li>
          <a href="">Fiverr</a>
        </li> -->
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      bulan: "",
      tanggal: "",
    };
  },
  methods: {
    date_function: function () {
      let currentDate = new Date().toJSON();
      console.log(currentDate);

      let bulan = new Date().toJSON().slice(5, 7).replace(/-/g, "/");
      this.bulan = bulan;

      let tanggal = new Date().toJSON().slice(8, 10).replace(/-/g, "/");
      this.tanggal = tanggal;
    },
  },
  mounted() {
    this.date_function();
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap");
* {
  font-family: "Poppins", sans-serif;
}
header {
  background-image: url(../assets/img/header.jpg);
  background-size: cover;
  background-position: center;
}
header::before {
  content: "";
  position: absolute;
  width: 100%;
  height: 50vh;
  bottom: 0;
  left: 0;
  background: linear-gradient(to top, rgb(0, 0, 0), rgba(0, 0, 0, 0));
}
</style>
