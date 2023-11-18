<template>
	<div id="app">
		<RotateBanner :list="list" />
	</div>
</template>

<script>
import RotateBanner from "./components/RotateBanner.vue";

export default {
	name: "App",
	components: {
		RotateBanner,
	},
	data() {
		return {
			list: [
				{
					id: 0,
					url: require("./assets/image/IMG_6481.jpeg"),
				},
				{
					id: 1,
					url: require("./assets/image/IMG_6455.jpeg"),
				},
				{
					id: 2,
					url: require("./assets/image/IMG_6150.jpeg"),
				},
				{
					id: 3,
					url: require("./assets/image/IMG_5983.jpeg"),
				},
				{
					id: 4,
					url: require("./assets/image/IMG_6529.jpeg"),
				},
			],
		};
	},
};
</script>

<style></style>
