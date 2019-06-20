<template>
  <div class="container is-fluid">
    <nav class="level">
      <p class="level-item has-text-centered">
        <nuxt-link class="link is-info" :to="{ name: 'index' }">Home</nuxt-link>
      </p>
      <p class="level-item has-text-centered">
        <nuxt-link class="link is-info" :to="{ name: 'work' }">Work</nuxt-link>
      </p>
      <p class="level-item has-text-centered">
        <img src="/images/miguelalcaino.png" alt="" />
      </p>
      <p class="level-item has-text-centered">
        <a
          class="link is-info"
          target="_blank"
          href="https://github.com/miguelalcaino"
          >Github</a
        >
      </p>
      <p class="level-item has-text-centered">
        <a
          class="link is-info"
          target="_blank"
          href="https://www.linkedin.com/in/miguelalcaino/"
          >LinkedIn</a
        >
      </p>
    </nav>
    <nuxt />
    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          The source code is licensed
          <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The
          website content is licensed
          <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/"
            >CC BY NC SA 4.0</a
          >.
        </p>
      </div>
    </footer>
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
</style>
