<template>
  <nav id="nav">
    <router-link to="/"></router-link>
    <router-link :to="{ name: 'home'}">Home</router-link> 
    <router-link :to="{ name: 'unit'}">Units</router-link>
    <router-link :to="{ name: 'campus'}">Campus</router-link>
    <router-link :to="{ name: 'login'}">login</router-link>
  </nav>
  <router-view/>

</template>

<style>
@import "/public/style.css";
</style>
