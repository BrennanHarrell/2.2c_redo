<template>
  <div class="app">
  
    <div class="top-menu">
      <img class="image" alt="Image" src="https://masternav.sync.deakin.edu.au/assets/img-deakin-logo-white-desktop.svg"/>
      <div class="logout">
        <router-link :to="{ path: '/login' }"><button class="btn">Logout</button></router-link>
      </div>
      
    </div>

    <div class="units">

      <button class="unit-1">SIT120</button>
      <button class="unit-2">SIT202</button>
      <button class="unit-3">SIT202</button>
      <button class="unit-4">SIT202</button>

    </div>

  <footer>

  </footer>

</div>


  
</template>

<style scoped>
@import "/public/units.css";
</style>
  

  