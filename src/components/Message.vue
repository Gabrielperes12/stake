<template>
    <div class="message-container">
      <p>{{ msg }}</p>
    </div>
  </template>
  
  <script>
    export default {
      name: "Message",
      props: {
        msg: String
      }
    }
  </script>
  
  <style scoped>
    .message-container {
      color: #f3b01f;
      background-color: #962613;
      border: 2px solid #f3b01f;
      border-radius: 5px;
      padding: 10px;
      max-width: 400px;
      margin: 30px auto;
    }
  </style>