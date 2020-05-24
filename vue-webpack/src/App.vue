<template>
	<div id="app">
		<!-- <app-message></app-message> -->

		<h1>Les't go some where!</h1>
		<hr>
		<!-- <a href="/">Home</a>
		<a href="/users">users</a> -->
		<router-link to="/">Home </router-link>
		<router-link to="/users/10">Users for team 10</router-link>
		<router-link to="/users/12">Users for team 12 </router-link>
		<hr>
		<router-view></router-view>
	</div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
		
    }
  }
}
</script>

<style>

</style>
