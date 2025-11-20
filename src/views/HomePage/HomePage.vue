<script setup>
import NavBar from '@/components/navbar/navbar.vue'
import HeaderView from '@/components/Header/HeaderView.vue'
import JobExplanation from '@/components/mainParts/jobExplanation/jobExplanation.vue';

</script>
<template>
  <header>
    <NavBar />
    <HeaderView />
  </header>
  <main>
  <JobExplanation/>
  </main>
</template>

<script>
export default {
  name: 'HomePage'
}
</script>

<style></style>
