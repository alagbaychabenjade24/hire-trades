<template>
	<div class="container">
		<Nav />
		<Homepage />
		<Footer />
	</div>
</template>

<script>
import Nav from './components/Nav';
import Homepage from './components/Homepage';
import Footer from './components/Footer';

export default {
	data: () => {
		return {};
	},
	name: 'App',
	components: {
		Nav,
		Homepage,
		Footer
	}
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
	font-family: 'Rubik', sans-serif;
	box-sizing: border-box;
	padding: 0;
	margin: 0;
	outline: none;
}

.minmax {
	width: 90%;
	max-width: 1140px;
	margin: 0 auto;
}
</style>
