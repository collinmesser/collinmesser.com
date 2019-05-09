<template>
  <div>
    <nav>
      <div class="nav">
        <a href="https://github.com/collinmesser/" target="_blank" class="navLink">GitHub</a>
        <a href="https://www.linkedin.com/in/collinmesser/" target="_blank" class="navLink">LinkedIn</a>
        <a href="https://twitter.com/collinmesser" target="_blank" class="navLink">Twitter</a>
        <a href="mailto:collin@collinmesser.com" target="_blank" class="navLink">Contact</a>
      </div>
    </nav>
    <section class="container">
      <div>
        <h1 class="title">
          Collin Messer
        </h1>
        <h2 class="subtitle">
          I am a Christ follower, husband, father, developer, blogger, problem solver, internet maker, human being. I love to build the internet, help people, and strive for 💯
        </h2>
        <div class="links">
          <a
            href="https://healthx.com/"
            target="_blank"
            class="hx-logo"
          >
            <hxLogo /> 
          </a>
          <a
            href="https://fiadventures.com"
            target="_blank"
            class="fiad-logo"
          >
            <fiadLogo />
          </a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import hxLogo from '~/components/hxLogo.vue'
import fiadLogo from '~/components/fiadLogo.vue'

export default {
  components: {
    hxLogo,
    fiadLogo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 90%;
}

nav {
  margin: 0 auto;
  width: 90%;
}

.nav {
  font-size: 1.25em;
  margin-top: 2em;
  text-align: right;
}

.navLink {
  color: #526488;
  margin-right: 1em;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 3em;
  color: #35495e;
}

.subtitle {
  font-weight: 300;
  font-size: 2em;
  color: #526488;
  padding-bottom: 15px;
}

.links {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  padding-top: 15px;
}

.links a {
  padding-bottom: 40px;
}
</style>
