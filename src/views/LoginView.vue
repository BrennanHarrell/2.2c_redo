<template>
    <div class="login-background">
    <div class="div">
      <div class="frame">
        <div class="frame-2">
          <p class="deakin-university">
            <span class="text-weight-deakin">
              Deakin University
              <br />
            </span>
            <span class="span">student portal</span>
          </p>
          <p class="p">Login to access your account</p>
        </div>
      </div>
        <div class="left-side">
            <div class="login-styling">
                <form @submit="submitted">
                    <div class="deakin-university">Login</div>
                    <div class="p-login">Enter your account details</div><br>
                    <input v-model.trim="newItem" type="text" placeholder="Student ID"><br>
                    <br>
                    <input v-model.trim="newItem" type="text" placeholder="Password">
                    <br>
                    <br>
                    <router-link :to="{ path: 'home' }"><input type="submit" value="Submit"></router-link>
                </form>
            </div>
        </div>
    </div>
  </div>

</template>

<style scoped>
@import "/public/login.css";
</style>


