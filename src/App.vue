<template>
	<div id="app">
		<div class="center">
			<img alt="Vue logo" src="./assets/logo.png" />
			<HelloWorld />
		</div>
	</div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
	name: "app",
	components: {
		HelloWorld
	}
};
</script>

<style>
/* reset.css */
@import "https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css";
.center {
	text-align: center;
}
</style>
