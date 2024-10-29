<template>
    <div class="skills-card">
      <h2 class="skills-title">Skills</h2>
      <p class="skills-details">
        I am passionate about gaming and coding, continuously improving my skills in software development while enjoying various gaming experiences.
      </p>
    </div>
  </template>
  
  <script>
  export default {
    name: "SkillsComponent",
  };
  </script>
  
  <style scoped>
  /* Skills Card Container */
  .skills-card {
      max-width: 300px;
      margin: 20px auto;
      padding: 20px;
      background-color: #2c2c2c;
      color: #ffffff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      text-align: center;
      font-family: Arial, sans-serif;
  }
  
  /* Skills Title */
  .skills-title {
      font-size: 20px;
      margin: 10px 0;
      color: #ffd700;
  }
  
  /* Skills Details */
  .skills-details {
      font-size: 14px;
      line-height: 1.5;
      color: #dcdcdc;
  }
  </style>
  