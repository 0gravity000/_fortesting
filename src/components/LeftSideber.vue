<template>
	<aside class="menu">
		<p class="menu-label">
			順列と組み合わせ
		</p>
		<ul class="menu-list">
			<li><a><router-link to="/permutation-and-combination-in-playingcard">トランプの順列と組み合わせ</router-link></a></li>
			<li><a><router-link to="/about">About</router-link></a></li>
		</ul>
	</aside>

</template>

<script>
export default {
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
