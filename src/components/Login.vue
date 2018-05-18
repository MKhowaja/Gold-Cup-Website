<template>
  <div class="login">
        <br>
        <b-container class="background-red">
            <h3 class="text-left text-white">Login</h3>
            <br>
            <div>
                <b-form-input v-model="email" type="text" placeholder="E-mail Address"></b-form-input>
                <br>
            </div>
            <div>
                <b-form-input v-model="password" type="password" placeholder="Password"></b-form-input>
                <br>
            </div>

            <div class="text-left">
                <router-link to="/forgotmypassword">
                    <a href="forgotmypassword" class="text-white"><u>Forgot your password?</u></a>
                </router-link>
            </div>

            <div class="text-right">
                <b-button href="login" class="background-gold text-white">Login</b-button>
            </div>
            <br>
            <p class="text-center text-white">Don't have an account? 
                <router-link to="/signup">
                    <a href="signup" class="text-gold">Sign up</a>
                </router-link>
            </p>
        </b-container>
  </div>
</template>

<script>
export default {
  name: 'login',
  data () {
    return {
      email: '',
      password: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

.text-gold {
    color:#CAA83F;
}

.background-red {
    background-color: #800505;
}

.background-gold {
    background-color:#CAA83F;
}

.btn-secondary {
    border-color:black;
    box-shadow: 0px 0px 0 0.5px black;
}

.btn {
    padding:0.375rem 2.75rem
}

.form-control {
    border-radius:0;
}
.container {
    padding-right:35px;
    padding-left:35px;
    padding-top:20px;
    padding-bottom:20px;
    margin-top:4rem;
    margin-bottom:6rem;
}

@media (min-width: 576px) {
    .container {
        max-width: 450px;
    }
}

@media (min-width: 768px) {
    .container {
        max-width: 450px;
    }
}

@media (min-width: 992px) {
    .container {
        max-width: 650px;
    }
}

@media (min-width: 1200px) {
    .container {
        max-width: 750px;
    }
}

</style>
