<template>
  <div class="home animate__animated animate__fadeIn animate__slow">
    <!-- <HelloWorld class="animate__animated animate__bounce" msg="Welcome to Your Vue.js App"/> -->


    <LogoComponent class="" :width="700" />
    <br>
		<NewMainComponent class=""/>
		<br>
		<!-- <MainPageContent /> -->

  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import LogoComponent from "@/components/LogoComponent";
import MainPageContent from "@/components/MainPageContent";
import NewMainComponent from "../components/NewMainComponent";


export default {
  name: 'Home',
  components: {
		NewMainComponent,

    LogoComponent,
    HelloWorld,
    MainPageContent
  }
}
</script>
<style scoped>
*{
	/*background-color: #cecccc;*/
}


</style>