<template>
  <nav class="navbar">
    <div class="left"><NuxtLink class="nav-link" to="/">Home</NuxtLink></div>
    <div class="left"><NuxtLink class="nav-link" to="/events">Events</NuxtLink></div>
    <login class="login" />
  </nav>
</template>

<style>

  .left {
    padding-right: 30px;
  }

  .navbar {
    display: flex;
    margin: 35px 76px;
    height: 50px;
    width: calc(100% - 152px);
    justify-content: left;
  }

  .nav-link {
    font-style: normal;
    font-weight: normal;
    font-size: 40px;
    line-height: 47px;
  }

  .login {
    margin-left: auto;
  }

</style>
