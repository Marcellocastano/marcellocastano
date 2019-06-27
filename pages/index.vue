<template>
  <div class="container">
    <header class="header2">
      <TopNav/>
    </header>
    <div class="content">
  		<AppLogo/>
  		<h1 class="title">
  		Site under constructions
  		</h1>
  		<h2 class="subtitle">
  		Nuxt.js project
  		</h2>
    </div>
    <footer>
      <Footer/>
    </footer>
  </div>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import TopNav from '~/components/top-nav.vue'
import Footer from '~/components/footer.vue'

export default {
  components: {
    AppLogo,
    TopNav,
    Footer
  }
}
</script>

<style>
header, footer {
  width: 100%;
}
.container {
	min-height: 100%;
	text-align: center;
}
.content {
  min-height: 70vh;
}
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 55px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

