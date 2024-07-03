<template>
    <div>
      <div class="main-container">
        <h1>Pedidos:</h1>
        <Dashboard />
      </div>
    </div>
  </template>
  
  <script>
  import Dashboard from '../components/Dashboard'
  import Footer from '../components/Footer'

  
  export default {
    name: 'Pedidos',
    components: {
      Dashboard,
      Footer
    }
  }
  </script>