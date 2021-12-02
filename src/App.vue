<!-- **************************************************** -->
<!-- **************************************************** -->
<template>
	<ListProducts  />
</template>

<!-- **************************************************** -->
<!-- **************************************************** -->

<script setup>

import ListProducts from './components/ListProducts.vue'
</script>

<!-- **************************************************** -->
<!-- **************************************************** -->

<style>
@import url("https://fonts.googleapis.com/css2?family=Ubuntu&display=swap");
* {
	padding: 0;
	margin: 0;
	box-sizing: border-box;
	list-style: none;
	font-family: "Ubuntu", sans-serif;
}
body {
	margin: 0 auto;
	background: rgba(254, 254, 254, 0.8);
	padding-bottom: 4rem;
	color: #333;
	overflow-x: hidden;
}
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
h1 {
  	margin: 3rem 0;
}
button {
	border: none;
	background: none;
	outline: none;
	cursor: pointer;
}
</style>
