<template>
    <div class="app">
    
      <div class="top-menu">
        <img class="image" alt="Image" src="https://masternav.sync.deakin.edu.au/assets/img-deakin-logo-white-desktop.svg"/>
        <div class="logout">
          <router-link :to="{ path: '/login' }"><button class="btn">Logout</button></router-link>
        </div>
        
      </div>

    <h1 class="content">
      Newsletter
    </h1>
  
  
    <nav id="nav">
      <router-link to="/"></router-link>
      <router-link :to="{ name: 'home'}">Home</router-link> 
      <router-link :to="{ name: 'unit'}">Units</router-link>
      <router-link :to="{ name: 'campus'}">Campus</router-link>
    </nav>
    <router-view/>
  
    <footer>
  
    </footer>

  </div>

    
  
  
    
  </template>
  
  <style>
  @import "/public/style.css";
  </style>
  