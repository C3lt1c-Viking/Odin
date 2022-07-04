<template>
  <header>
    <img alt="Vue logo" src="../assets/odin.jpg" height="50">
    <p>Odin</p>
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
        <li><router-link to="/data">Database</router-link></li>
        <li><router-link to="/twitter">Twitter API</router-link></li>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss">
</style>
<style lang="scss">
/*
font-family: 'Cinzel', serif;
font-family: 'Orbitron', sans-serif;
font-family: 'Play', sans-serif;
font-family: 'Rubik Moonrocks', cursive;
font-family: 'Space Mono', monospace;
font-family: 'Stick No Bills', sans-serif;
*/
  header {
    display: flex;
    border-bottom: 1px solid #ccc;
    padding: .5rem 1rem;

    p {
      margin-left: 1rem;
      margin-top: -1px;
      font-family: 'Rubik Moonrocks', cursive;
      font-size: 30px;
    }
  }

  nav {
    margin-left: auto;

    ul {
      list-style: none;
    }

    ul li {
      display: inline-flex;
      margin-left: 1rem;
      font-family: 'Orbitron', sans-serif;
      font-size: 20px;
    }
  }
</style>
