<template>
  <div class="signup">
        <br>
        <b-container>
            <h3 class="text-left text-red">Create a User Account</h3>
            <b-container class="background-gray outline-gray">
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

                <div class="text-left">
                    <b-button href="login" class="background-red text-white">Sign Up</b-button>
                </div>
            </b-container>
        </b-container>
  </div>
</template>

<script>
export default {
  name: 'signup',
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

.text-red {
    color: #800505;
}

.background-red {
    background-color: #800505;
}

.background-gold {
    background-color:#CAA83F;
}

.background-gray {
    background-color: #F2F2F2;
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

</style>
