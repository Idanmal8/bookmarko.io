<template>
    <div class="policies-page">
      <img
        alt="Mascot"
        class="mascot-logo"
        src="@/assets/ghost_lobby.png"
      />
      
      <div class="policies-content">
        <h1 class="policies-heading">
          <slot name="heading">Policy & Terms</slot>
        </h1>
        <div class="policies-body">
          <slot name="body">
            <p>Your policy content goes here...</p>
          </slot>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  // no logic needed for now — purely presentational
  </script>
  
  <style scoped>
  .policies-page {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 40px 16px;
    width: 100%;
    max-width: 800px; /* Set a max-width for readability */
    box-sizing: border-box;
  }
  
  .policies-content {
    width: 100%;
    box-sizing: border-box;
  }
  
  .mascot-logo {
    width: 125px;
    height: 125px;
    margin-bottom: 24px;
  }
  
  .policies-heading {
    font-size: 2rem;
    font-weight: bold;
    margin-bottom: 16px;
    text-align: center;
  }
  
  .policies-body {
    font-size: 1rem;
    line-height: 1.6;
    color: #222;
    text-align: left;
    width: 100%; /* Ensure the text content takes full width */
  }
  </style>
