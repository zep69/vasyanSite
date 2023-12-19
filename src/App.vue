<template>
	<div class="app">
		<HeaderComponent class="animate__animated animate__slideInDown" style="z-index: 5"/>
		<!-- <div id="nav">
			<router-link to="/">Home</router-link> |
			<router-link to="/about">About</router-link>
		</div> -->
		<transition name="bounce" >
			<router-view   />
		</transition>

	</div>

</template>
<script>
import HeaderComponent from "./components/HeaderComponent";
export default {
	components:{
		HeaderComponent
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
*{
	margin:0;
	padding: 0;
	box-sizing: border-box;
	background-color: #cecccc;
	z-index: 1;

}
.app{
	background-color: #cecccc;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.bounce-enter-active {
	animation: bounce-in .5s;
}
.bounce-leave-active {
	animation: bounce-in .5s reverse;
}
@keyframes bounce-in {
	0% {
		transform: scale(0);
	}
	50% {
		transform: scale(1.5);
	}
	100% {
		transform: scale(1);
	}
}

</style>
