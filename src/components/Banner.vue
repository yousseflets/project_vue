<template>
    <div id="main-banner"></div>

    <div >
      <div id="main-home">
        <h1>
          <p class="sobre">SOBRE O</p>
          <p class="name">YOUSSEF BURGER</p>
          <p class="texto">
            Nascemos em Mogi das Cruzes, com a proposta de trazer um diferencial para as hamburguerias da região. 
            Nosso maior desejo é proporcionar uma experiência completa para nossos clientes, com um ambiente agradável e 
            cheio de conforto, atendimento dedicado e lanches mais do que especiais, com receitas exclusivas e artesanais. 
            Com ingredientes selecionados, molhos artesanais e carnes frescas de altíssima qualidade, montamos burgers e 
            porções cheios de sabor, para entregar a você uma refeição inesquecível!
          </p>
          <br/>
          <router-link class="submit-btn" to="/fazer-pedidos">Fazer Pedido</router-link>
        </h1>
      </div>
    </div>
  </template>
  
  <script>
    export default {
      name: "Banner"
    }
  </script>
  
  <style scoped>
  
    #main-banner {
      background-image: url('/public/img/youssefBurger.png');
      background-position: 0 -130px;
      background-size: cover;
      height: 550px;
      display: flex;
      align-items: center;
      justify-content: flex-start;
      background-repeat: no-repeat;
    }

    #main-home {
      background-image: url('/public/img/burgerHome.jpg');
      background-position: 0 -250px;
      background-size: cover;
      background-repeat: no-repeat;
      height: 600px;
      width: 600px;
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 50px;
      top: 30%;
      transform: translate(30%, 20%);
    }
  
    #main-home h1 {
      color: #000;
      text-align: left;
      justify-content: left;
      font-size: 13px;
      background-color: #fff;
      padding: 10px 20px;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(20%, -50%);
      width: 100%;
      box-shadow: 5px 10px 50px #dddcdc;
      border-radius: 25px;
      margin: 24px;
    }

    #main-home .sobre {
      color: #fa5a04;
      font-family: "Permanent Marker", cursive;
      font-size: 32px;
    }

    #main-home .name {
      color: #000;
      font-family: "Chakra Petch", sans-serif;
      font-size: 38px;
    }

    #main-home .texto {
      color: #000;
      font-family: "Arsenal SC", sans-serif;
      font-size: 22px;
    }

  
    .submit-btn {
      background-color: white; 
      color: black; 
      font-weight: bold;
      border: 2px solid ;
      padding: 10px;
      font-size: 18px;
      margin: 0 auto;
      cursor: pointer;
      transition: .5s;
      transform: translate(100%, -30%);
      left: 100%;
      border-radius: 25px;
      width: 180px;
      display: flex;
      text-align: center;
      justify-content: center;
      font-family: "Permanent Marker", cursive;
      font-weight: 400;
      font-style: normal;
    }

    .submit-btn:hover {
      background-color: #f44336;
      color: white;
    }

    .submit-btn a {
      color: #000;
      text-decoration: none;
      margin: 12px;
      transition: .5s;
    }
  
    .submit-btn a:hover {
      color: #fa5a04;
    }
  </style>