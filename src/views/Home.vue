<template>
  <div class="home">
    <b-container>
      <b-row align-v="center">
        <job-card></job-card>
        <job-card></job-card>
        <job-card></job-card>
        <job-card></job-card>
    </b-row>
</b-container>
  </div>
</template>

<script>
import JobCard from '@/components/JobCard.vue';

export default {
  name: "Home",
  components: {"job-card": JobCard}
};
</script>
