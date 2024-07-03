<template>
    <div>
        <div class="main-container">
            <h1>Monte seu lanche:</h1>
            <BurgerForm />
        </div>
    </div>
  </template>
  <script>
  import Navbar from '../components/Navbar'
  import Footer from '../components/Footer'
  import BurgerForm from '../components/BurgerForm'
  
  export default {
    data: function() {
      return {
        logo_src: "/img/logo.png",
        app_name: "Youssef Burger"
      }
    },
    components: {
        Navbar,
        Footer,
        BurgerForm
    }
  }
  </script>
  
  <style>
    * {
      font-family: Helvetica;
      padding: 0;
      margin: 0;
      box-sizing: border-box;
    }
  
    .main-container {
      margin: 50px;
      min-height: 250px;
    }
  
    h1 {
      text-align: center;
      font-size: 42px;
      margin-bottom: 30px;
      color: #222;
      font-family: "Arsenal SC", sans-serif;
    }
  </style>