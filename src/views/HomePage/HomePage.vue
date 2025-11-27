<script setup>
import NavBar from '@/components/navbar/navbar.vue'
import HeaderView from '@/components/Header/HeaderView.vue'
import JobExplanation from '@/components/mainParts/jobExplanation/jobExplanation.vue'
import AboutMe from '@/components/mainParts/AboutMe/AboutMe.vue'
import SkillsPart from '@/components/mainParts/SkillsPart/SkillsPart.vue'
</script>
<template>
  <header>
    <NavBar />
    <HeaderView />
  </header>
  <main>
    <JobExplanation />
    <AboutMe />
    <SkillsPart/>
  </main>
</template>

<script>
export default {
  name: 'HomePage'
}
</script>

<style></style>
