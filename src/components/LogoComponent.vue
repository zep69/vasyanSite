<template>
  <img src="../assets/vasyanLogo.png" :style="{width:$props.width+'px', background:'none'}" alt="">
</template>

<script>
export default {
  name: "Logo component",
  props:{
    width:{
      type:String,
      default(){
        return '300'
      }
    }
  },
  data(){
    return{

    }
  },
  methods:{

  },
  async mounted(){

  }
}
</script>

<style scoped>

</style>