<template>
  <div class="home">
    <!-- <HelloWorld class="animate__animated animate__bounce" msg="Welcome to Your Vue.js App"/> -->
    <LogoComponent class="animate__animated animate__slideInDown" :width="700" />
    <br>
    <MainPageContent />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import LogoComponent from "@/components/LogoComponent";
import MainPageContent from "@/components/MainPageContent";


export default {
  name: 'Home',
  components: {
    LogoComponent,
    HelloWorld,
    MainPageContent
  }
}
</script>
