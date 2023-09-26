<template>
  <div class="app">
    
      <div class="top-menu">
        <img class="image" alt="Image" src="https://masternav.sync.deakin.edu.au/assets/img-deakin-logo-white-desktop.svg"/>
        <div class="logout">
          <router-link :to="{ path: '/login' }"><button class="btn">Logout</button></router-link>
        </div>

        
        
      </div>
      <div>
        <header class="content">
          <h2>Your campus location:</h2>
        </header>
      </div>
      
      <div class="google-map">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6271.096842460701!2d144.29507320273729!3d-38.19716241155729!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad412d2b2e0033b%3A0x3503ccd64f2681a4!2s75%20Pigdons%20Rd%2C%20Waurn%20Ponds%20VIC%203216!5e0!3m2!1sen!2sau!4v1695726599222!5m2!1sen!2sau" 
        width="600" height="450" style="border:0;" allowfullscreen="false" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>

  <footer>
  
  </footer>

  
  </div>
    

</template>

<style scoped>
@import "/public/campus.css";
</style>