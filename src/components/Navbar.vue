<template>
    <div>
      <div id="nav">
        <router-link id="logo-url" to="/">
          <img id="logo" :src="logo" :alt="alt">
        </router-link>
        <router-link to="/fazer-pedidos">Fazer Pedido</router-link>
        <router-link to="/pedidos">Pedidos</router-link>
      </div>
    </div>
  </template>
  
  <script>
  
  export default {
    name: "Navbar",
    props: ["logo", "alt"]
  }
  </script>
  
  <style scoped>
    #nav {
      background-color: #000000;
      border-bottom: 4px solid #fa5a04;
      padding: 15px 50px;
      display: flex;
      justify-content: flex-end;
      align-items: center;
    }
  
    #nav #logo-url {
      margin: auto;
      margin-left: 0;
    }
  
    #logo {
      width: 40px;
      height: 40px;
    }
  
    #nav a {
      color: #fff;
      text-decoration: none;
      margin: 12px;
      transition: .5s;
    }
  
    #nav a:hover {
      color: #fa5a04;
    }
  </style>