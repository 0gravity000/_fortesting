<template>
  <div id="nav">
		<Navbar />
  </div>
  <router-view/>
	<div class="container">
	<div class="columns">
		<div class="column is-one-third">
			<LeftSideber />
		</div>
		<div class="column">
			<MainContents />
		</div>
	</div>
	</div>
	<Footer />
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import MainContents from '@/components/MainContents.vue'
import LeftSideber from '@/components/LeftSideber.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'App',
  components: {
		Navbar,
		MainContents,
		LeftSideber,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
