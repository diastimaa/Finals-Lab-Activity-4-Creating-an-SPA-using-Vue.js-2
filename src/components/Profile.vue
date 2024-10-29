<template>
    <div class="profile-card">
      <h2 class="profile-name">Profile</h2>
      <p class="profile-info">I'm Andrei Jovic Laurel</p>
      <p class="profile-bio">
        Passionate gamer with over X years of experience, enjoys strategy, adventure, and immersive worlds. Team player, eager to try new genres and level up skills.
      </p>
    </div>
  </template>
  
  <script>
  export default {
    name: "ProfileComponent",
  };
  </script>
  
  <style scoped>
  /* Profile Card Container */
  .profile-card {
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
  
  /* Profile Name */
  .profile-name {
      font-size: 24px;
      margin: 10px 0;
      color: #ffd700;
  }
  
  /* Profile Info */
  .profile-info {
      font-size: 16px;
      font-weight: bold;
  }
  
  /* Profile Bio */
  .profile-bio {
      font-size: 14px;
      line-height: 1.5;
      color: #dcdcdc;
  }
  </style>
  