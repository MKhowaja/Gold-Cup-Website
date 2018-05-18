<template>
    <b-navbar toggleable="md" type="dark" variant="info">

    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

    <router-link to="/">
      <b-navbar-brand href="">Gold Cup Logo</b-navbar-brand>
    </router-link>
    <b-collapse is-nav id="nav_collapse">

        <b-navbar-nav>
            <!-- Logo goes here -->
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <router-link to="/info">
            <b-nav-item href="info">Info</b-nav-item>
          </router-link>
          <router-link to="/schedule">
            <b-nav-item href="schedule">Schedule</b-nav-item>
          </router-link>
          <router-link to="/calendar">
            <b-nav-item href="calendar">Calendar</b-nav-item>
          </router-link>
          <router-link to="/blog">
            <b-nav-item href="blog">Blog</b-nav-item>
          </router-link>
          <router-link to="/contact">
            <b-nav-item href="contact">Contact</b-nav-item>
          </router-link>
          <router-link to="/login">
            <b-nav-item href="login">Login</b-nav-item>
          </router-link>
        </b-navbar-nav>

    </b-collapse>
    </b-navbar>
</template>

<script>
  module.exports = {
    data () {
      return {}
    }
  }
</script>

<style scoped>
.bg-info {
    background-color: #800505!important;
}

.navbar {
  padding: 1.5rem 5rem;
  font-size: 0.6rem
}

.navbar-dark .navbar-nav .nav-link {
    color: rgba(255,255,255);
}
</style>