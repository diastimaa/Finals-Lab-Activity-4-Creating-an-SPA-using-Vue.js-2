<template>
  <div id="app">
    <h1>My Resume</h1>
    <ProfileComponent />
    <EducationComponent />
    <SkillsComponent />
  </div>
</template>

<script>
import ProfileComponent from "./components/Profile.vue";
import EducationComponent from "./components/Education.vue";
import SkillsComponent from "./components/Skills.vue";

export default {
  name: "App",
  components: {
    ProfileComponent,
    EducationComponent,
    SkillsComponent,
  },
};
</script>

<style scoped>
/* App Container */
html, body {
  margin: 0; /* Remove default margins */
  height: 100%; /* Full height */
  font-family: Arial, sans-serif; /* Consistent font style */
}

#app {
  min-height: 100vh; /* Ensure it covers the entire viewport height */
  padding: 20px; /* Add padding for spacing */
  background-color: #1e1e1e; /* Dark background for contrast */
  color: #ffffff; /* White text color for visibility */
  border-radius: 0; /* Remove border radius for full coverage */
  box-shadow: none; /* Remove shadow for a flat look */
  display: flex; /* Use flexbox for layout */
  flex-direction: column; /* Stack elements vertically */
  align-items: center; /* Center items horizontally */
  justify-content: flex-start; /* Align items to the top */
}

/* App Title */
h1 {
  text-align: center; /* Center the title */
  color: #ffd700; /* Gold color for the title */
  margin-bottom: 20px; /* Spacing below the title */
  font-size: 24px; /* Font size for the title */
}
</style>
