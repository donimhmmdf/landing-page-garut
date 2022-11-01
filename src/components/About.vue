<template>
  <section id="about" class="px-4 w-full mt-4">
    <div class="about-container container m-auto lg:w-3/4">
      <div
        class="image-gallery font-bold text-2xl w-full lg:flex min-h-[300px] mb-16 justify-between"
      >
        <div class="image-box w-full lg:w-1/6 h-60 mb-4 relative">
          <img
            class="w-full h-full object-cover absolute transition duration-300 hover:opacity-50"
            src="../assets/img/1.jpg"
            alt=""
          />
          <h2 class="absolute -bottom-4 right-20 hidden lg:block">G</h2>
        </div>
        <div class="image-box w-full lg:w-1/6 h-60 mb-4 relative">
          <img
            class="w-full h-full object-cover absolute transition duration-300 hover:opacity-50"
            src="../assets/img/2.jpg"
            alt=""
          />
          <h2 class="absolute -bottom-4 right-20 hidden lg:block">A</h2>
        </div>
        <div class="image-box w-full lg:w-1/6 h-60 mb-4 relative">
          <img
            class="w-full h-full object-cover absolute transition duration-300 hover:opacity-50"
            src="../assets/img/3.jpg"
            alt=""
          />
          <h2 class="absolute -bottom-4 right-20 hidden lg:block">R</h2>
        </div>
        <div class="image-box w-full lg:w-1/6 h-60 mb-4 relative">
          <img
            class="w-full h-full object-cover absolute transition duration-300 hover:opacity-50"
            src="../assets/img/5.jpg"
            alt=""
          />
          <h2 class="absolute -bottom-4 right-20 hidden lg:block">U</h2>
        </div>
        <div class="image-box w-full lg:w-1/6 h-60 mb-4 relative">
          <img
            class="w-full h-full object-cover absolute transition duration-300 hover:opacity-50"
            src="../assets/img/6.jpg"
            alt=""
          />
          <h2 class="absolute -bottom-4 right-20 hidden lg:block">T</h2>
        </div>
      </div>
      <div class="about mb-10 text-center font-medium">
        <h2 class="font-xl">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium
          possimus temporibus recusandae, nemo eos fugiat dolorem deleniti aut,
          nulla expedita nostrum ab quidem! Aspernatur nam culpa suscipit id
          aliquam deleniti?
        </h2>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
body {
  background-color: black;
  color: white;
}
.image-box:nth-child(even) {
  align-self: flex-end;
}
.image-box h2 {
  font-style: italic;
}
</style>
