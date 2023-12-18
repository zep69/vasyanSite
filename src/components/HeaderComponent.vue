<template>
	<div class="header">
		<div class="componentsHeader">
			<LogoComponent style="align-self: center; background-color: grey;" width="100"/>
			<div class="buttons">
				<div v-for="item in buttons" style="background-color: grey;">
					<button>{{item.name}}</button>
				</div>

			</div>
		</div>
	</div>
</template>

<script>
import LogoComponent from "./LogoComponent";
export default {
	name: "HeaderComponent",
	components:{
		LogoComponent
	},
	data(){
		return {
			buttons:[
				{name:'Проекты'},
				{name:'Сотрудники'},
				{name:'Планы'}
			]
		}
	}
}
</script>

<style scoped>
	.buttons{
		display: flex;
		margin-left: 10px;
		background-color: grey;
	}
	button{
		background: none;
		border: none;
		margin: 0 5px 0 5px;
		font-family: Roboto;
		color: #cecccc;
		font-size: 20px;


	}
	.header{
		max-height: 75px;
		background-color: grey;
		border: none;
		height: 70px;
		width: 100%;
		-webkit-box-shadow: -2px 11px 12px -4px rgba(0, 0, 0, 0.2);
		-moz-box-shadow: -2px 11px 12px -4px rgba(0, 0, 0, 0.2);
		box-shadow: -2px 11px 12px -4px rgba(0, 0, 0, 0.2);
	}
	.componentsHeader{
		background-color: grey;
		display: flex;
		align-items: center;
		height: 100%;
		margin: 0 10px 0 10px;
	}
</style>