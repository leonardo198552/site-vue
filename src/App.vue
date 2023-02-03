<template>
  <div id="app">
    <nav>
      <ul>
        <li>
          <router-link to="/">Home</router-link>
        </li>
        <li>
          <router-link to="/about">Sobre</router-link>
        </li>
        <li>
          <router-link to="/contact">Contato</router-link>
        </li>
      </ul>
    </nav>
    <router-view />
  </div>
  <div id="app">
    <header>
      <img src="@/assets/logo.png" alt="Logo">
      <nav>
        <a href="#">Teste</a>
      </nav>
    </header>
    <main>
      <router-view />
    </main>
  </div>
</template>

<style>
  nav {
    font-size: 30px;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    background-color: #ffffff;
    color: #000000;
  }

  ul {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
  }

  li {
    margin: 0 30px;
  }

  a {
    display: block;
    padding: 20px;
    color: #fff;
    text-decoration: none;
  }

  a:hover {
    background-color: #444;
  }
  header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px;
}

header img {
  width: 50px;
  height: 50px;
}
</style>

