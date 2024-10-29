<template>
    <div class="education-card">
      <h2 class="education-title">Education</h2>
      <p class="education-details">
        Currently studying at Holy Angel University, taking BSIT - Web Development, and a 3rd-year student.
      </p>
    </div>
  </template>
  
  <script>
  export default {
    name: "EducationComponent",
  };
  </script>
  
  <style scoped>
  /* Education Card Container */
  .education-card {
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
  
  /* Education Title */
  .education-title {
      font-size: 20px;
      margin: 10px 0;
      color: #ffd700;
  }
  
  /* Education Details */
  .education-details {
      font-size: 14px;
      line-height: 1.5;
      color: #dcdcdc;
  }
  </style>
  