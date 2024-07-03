
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
      color: #FFF;
      background-color: #00fc19;
      border: 2px solid #03ff086c;
      border-radius: 5px;
      padding: 10px;
      max-width: 400px;
      margin: 30px auto;
    }
  </style>
  