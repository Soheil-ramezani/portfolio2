<template>
  <section class="AboutMe py-[10%] flex flex-col items-center">
    <!-- title  -->
    <h1 class="AboutMe__h1 montserrat-500 mb-20 text-[30px] px-8 py-5">About Me</h1>
    <!-- short text -->
    <p
      v-show="!this.showLongText"
      class="AboutMe__p max-w-[70%] font-sans text-[15px] text-center leading-8"
    >
      Hi there! My name is Soheil Ramazani, and I'm a front-end developer driven by a passion for
      building beautiful and interactive user experiences.Specializing in Vue, I thrive on taking
      intricate concepts and turning them into intuitive and captivating user interfaces
    </p>
    <!-- long text -->
    <p
      v-show="this.showLongText"
      class="AboutMe__p max-w-[70%] font-sans text-[15px] text-center leading-8"
    >
      Hi there! My name is Soheil Ramazani, and I'm a front-end developer driven by a passion for
      building beautiful and interactive user experiences. Specializing in Vue, I thrive on taking
      intricate concepts and turning them into intuitive and captivating user interfaces. My
      professional philosophy is built upon team collaboration, continuous learning, and creative
      problem-solving. I consistently seek out new technologies to master and enjoy improving my
      abilities while actively engaging with the developer community. I'm looking for opportunities
      where I can contribute to innovative and impactful product development as part of a dynamic
      and creative team.You can also watch some of my project down there!
    </p>
    <!--short text btn  -->
    <button v-show="!this.showLongText" @click="changeText()" class="AboutMe__btn px-10 mt-20">
      more explanation
    </button>
    <!--Long text btn  -->
    <button v-show="this.showLongText" @click="changeText()" class="AboutMe__btn px-10 mt-20">
      less explanation
    </button>
    <!-- separate part svg -->
    <svg class="AboutMe__svg mt-[5%]" width="200" height="50">
      <!-- straight lines -->
      <line x1="0" y1="25" x2="50" y2="25" stroke="black" stroke-width="2.5" />
      <line x1="150" y1="25" x2="200" y2="25" stroke="black" stroke-width="2.5" />
      <!-- right lines -->
      <line x1="110" y1="30" x2="120" y2="20" stroke="black" stroke-width="2.5" />
      <line x1="120" y1="30" x2="130" y2="20" stroke="black" stroke-width="2.5" />
      <!-- v lines -->
      <polyline points="  90,20 100,30 110,20 " stroke="black" stroke-width="2.5" fill="none" />
      <!-- left lines -->
      <line x1="80" y1="20" x2="90" y2="30" stroke="black" stroke-width="2.5" />
      <line x1="70" y1="20" x2="80" y2="30" stroke="black" stroke-width="2.5" />
    </svg>
    <!-- jobAbility -->
    <div
      class="jobAbility w-full my-[5%] mx-[15%] pl-[15%] flex flex-row justify-center items-center flex-wrap gap-y-11"
    >
      <!-- ability 1 -->
      <div class="ability w-1/2">
        <h2 class="ability__h2 montserrat-500 text-[22px]">Development</h2>
        <p class="ability__p text-[14px] font-sans max-w-[70%]">
          I build websites incorporating effective Design Systems and adhering to Clean Code
          principles.
        </p>
      </div>
      <!-- ability 1 -->
      <div class="ability w-1/2">
        <h2 class="ability__h2 montserrat-500 text-[22px]">Design</h2>
        <p class="ability__p text-[14px] font-sans max-w-[70%]">
          I help establish stability and efficiency on your website through design based on UI/UX
          development standards.
        </p>
      </div>
      <!-- ability 1 -->
      <div class="ability w-1/2">
        <h2 class="ability__h2 montserrat-500 text-[22px]">Maintenance</h2>
        <p class="ability__p text-[14px] font-sans max-w-[70%]">
          Standardized coding and Clean Code lower your website's maintenance and development costs.
        </p>
      </div>
    </div>
    <!-- separate part svg -->
    <svg class="AboutMe__svg mt-[5%]" width="200" height="50">
      <!-- straight lines -->
      <line x1="0" y1="25" x2="50" y2="25" stroke="black" stroke-width="2.5" />
      <line x1="150" y1="25" x2="200" y2="25" stroke="black" stroke-width="2.5" />
      <!-- right lines -->
      <line x1="110" y1="30" x2="120" y2="20" stroke="black" stroke-width="2.5" />
      <line x1="120" y1="30" x2="130" y2="20" stroke="black" stroke-width="2.5" />
      <!-- v lines -->
      <polyline points="  90,20 100,30 110,20 " stroke="black" stroke-width="2.5" fill="none" />
      <!-- left lines -->
      <line x1="80" y1="20" x2="90" y2="30" stroke="black" stroke-width="2.5" />
      <line x1="70" y1="20" x2="80" y2="30" stroke="black" stroke-width="2.5" />
    </svg>
  </section>
</template>

<script>
export default {
  name: 'AboutMe',
  data() {
    return {
      showLongText: false
    }
  },
  methods: {
    changeText() {
      this.showLongText = !this.showLongText
    }
  }
}
</script>

<style></style>
