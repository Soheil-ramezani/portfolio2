<template>
  <section class="AboutMe py-[10%] flex flex-col items-center">
    <h1 class="AboutMe__h1 montserrat mb-20 text-[30px] px-8 py-5">About Me</h1>
    <p v-show="!this.showLongText" class="AboutMe__p max-w-[70%] font-sans text-[15px] text-center leading-8">
      Hi there! My name is Soheil Ramazani, and I'm a front-end developer driven by a passion for
      building beautiful and interactive user experiences.Specializing in Vue, I thrive on taking
      intricate concepts and turning them into intuitive and captivating user interfaces
    </p>
    <p v-show="this.showLongText" class="AboutMe__p max-w-[70%] font-sans text-[15px] text-center leading-8">
      Hi there! My name is Soheil Ramazani, and I'm a front-end developer driven by a passion for
      building beautiful and interactive user experiences. Specializing in Vue, I thrive on taking
      intricate concepts and turning them into intuitive and captivating user interfaces. My
      professional philosophy is built upon team collaboration, continuous learning, and creative
      problem-solving. I consistently seek out new technologies to master and enjoy improving my
      abilities while actively engaging with the developer community. I'm looking for opportunities
      where I can contribute to innovative and impactful product development as part of a dynamic
      and creative team.You can also watch some of my project down there!
    </p>
    <button v-show="!this.showLongText" @click="changeText()" class="AboutMe__btn px-10 mt-20">
      more explanation
    </button>
    <button v-show="this.showLongText" @click="changeText()" class="AboutMe__btn px-10 mt-20">
      less explanation
    </button>
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

<style>
</style>