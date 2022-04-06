<template>
	<div class="container">
  <div id="nav">
		<Navbar />
  </div>
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
  color: #2c3e50;
}

</style>
