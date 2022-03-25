<template>
  <div>
    <header>Este es un header</header>
    <!-- nav -->
    <nav>
      <ul>
        <li>
          <router-link to="/">Home</router-link>
        </li>
        <li>
          <router-link to="/about">About</router-link>
        </li>
        <li>
          <router-link to="/contact">Contact</router-link>
        </li>
      </ul>
    </nav>
    <button>Botton</button>
    <main>
      <router-view></router-view>
    </main>
    <footer>
      <p>Este es un footer</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
