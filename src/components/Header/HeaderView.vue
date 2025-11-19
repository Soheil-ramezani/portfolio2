<template>
  <section class="header py-10 flex flex-row justify-around">
    <!-- Left side -->
    <div class="leftSide w-2/5">
      <h3 class="leftSide__h3 text-[40px] raleway-400 ">Hi, I'm</h3>
      <h1 class="leftSide__h1 text-[80px] alegreya-sc-extrabold">Soheil Ramezani</h1>
      <h2 class="leftSide__h2">Front-end Developer</h2>
    </div>
    <!-- Right side -->
    <div class="rightSide w-2/5 z-10">
      <div class="rightSideBtns w-full pl-[10%] flex flex-row justify-start items-center gap-8">
        <button class="rightSideBtns__btn text-white px-2 py-1">About ME</button>
        <button class="rightSideBtns__btn text-white px-2 py-1">Skills</button>
        <button class="rightSideBtns__btn text-white px-2 py-1">Portfolio</button>
        <button class="rightSideBtns__btn text-white px-2 py-1 selected">Concat Me</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'headerView'
}
</script>

<style></style>
