<template>
  <div class="home">
    <b-container>
      <b-row align-v="center">
        <JobCard />
        <JobCard />
        <JobCard />
        <JobCard />
        <JobCard />
        <JobCard />
      </b-row>
    </b-container>
  </div>
</template>

<script>
import JobCard from "../components/JobCard";

export default {
  name: "home",
  components: {
    JobCard
  }
};
</script>
