<template>
  <section class="Skills flex flex-col items-center">
    <!-- title  -->
    <h1 class="Skills__h1-title montserrat-500 mb-20 text-[30px] pt-2 text-center">S K I L L S</h1>
    <!-- skills list -->
    <div class="Skills-list flex flex-col gap-20 justify-between items-start w-[70%]">
      <!-- Using now -->
      <h1 class="Skills__h1 montserrat-500 text-[30px]">USING NOW:</h1>
      <div class="Skills-icons w-full grid grid-cols-4 gap-8">
        <!-- Html -->
        <div class="skill flex flex-col items-center gap-2">
          <img src="../../../assets/photos/svg/html.svg" alt="HTML5 icon" class="skill__img" />
          <span class="skill__span text-[24px] montserrat-500"> HTML 5 </span>
        </div>
        <!-- css -->
        <div class="skill flex flex-col items-center gap-2">
          <img src="../../../assets/photos/svg/css.svg" alt="CSS icon" class="skill__img" />
          <span class="skill__span text-[24px] montserrat-500"> CSS</span>
        </div>
        <!-- js -->
        <div class="skill flex flex-col items-center gap-2">
          <img
            src="../../../assets/photos/svg/javascript-logo-svgrepo-com.svg"
            alt="JS icon"
            class="skill__img"
          />
          <span class="skill__span text-[24px] montserrat-500"> Java Script</span>
        </div>
        <!-- VUE3 -->
        <div class="skill flex flex-col items-center gap-2">
          <img
            src="../../../assets/photos/svg/vue-vuejs-javascript-js-framework-svgrepo-com.svg"
            alt="vue3 icon"
            class="skill__img"
          />
          <span class="skill__span text-[24px] montserrat-500"> vue3 </span>
        </div>
        <!-- Tailwind -->
        <div class="skill flex flex-col items-center gap-2">
          <img
            src="../../../assets/photos/svg/tailwind-svgrepo-com.svg"
            alt="Tailwind icon"
            class="skill__img"
          />
          <span class="skill__span text-[24px] montserrat-500"> TAILWIND </span>
        </div>
        <!-- bootstrap -->
        <div class="skill flex flex-col items-center gap-2">
          <img
            src="../../../assets/photos/svg/bootstrap.svg"
            alt="bootstrap icon"
            class="skill__img"
          />
          <span class="skill__span text-[24px] montserrat-500"> BOOTSTRAP </span>
        </div>
        <!-- sass -->
        <div class="skill flex flex-col items-center gap-2">
          <img
            src="../../../assets/photos/svg/sass.svg"
            alt="sass icon"
            class="skill__img"
          />
          <span class="skill__span text-[24px] montserrat-500"> SASS </span>
        </div>
        <!-- sass -->
        <div class="skill flex flex-col items-center gap-2">
          <img
            src="../../../assets/photos/svg/git.svg"
            alt="git icon"
            class="skill__img"
          />
          <span class="skill__span text-[24px] montserrat-500"> GIT </span>
        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'skillsPart'
}
</script>

<style></style>
