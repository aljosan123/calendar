<template>
  <div id="app">
    <b-navbar type="dark" variant="info">
      <b-navbar-brand>Calendar</b-navbar-brand>
      <b-navbar-nav>
        <b-nav-item to="/">Home</b-nav-item>
        <b-nav-item to="/about">About</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
  <div>
    <router-view ></router-view>
  </div>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
