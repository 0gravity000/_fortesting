<template>
  <div class="maincontents">
	<router-view/>
  </div>
</template>

<script>
export default {
	data () {
		return {
			pagename: 'test'
		} 
	},
  props: {
    msg: String
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
