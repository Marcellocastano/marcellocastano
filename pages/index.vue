<template>
  <section class="container">
  <TopNav/>
    <div class="content">
  		<AppLogo/>
  		<h1 class="title">
  		Site under construction	
  		</h1>
  		<h2 class="subtitle">
  		Nuxt.js project
  		</h2>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import TopNav from '~/components/top-nav.vue'

export default {
  components: {
    AppLogo,
    TopNav
  }
}
</script>

<style>
.container {
	min-height: 100vh;
	display: flex;
	justify-content: flex-start;
	align-items: center;
	text-align: center;
	background-image: url(https://images.unsplash.com/photo-1506744038136-46273834b3fb?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80);
	background-repeat: no-repeat;
	background-size: cover;
	flex-direction: column;
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

