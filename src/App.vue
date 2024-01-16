<script>
export default{
  data(){
return{
  test:"",
  signInPayload:{
mobile:'',
password:''
  }
}
  },
  methods:{
    signIn(){
    console.log(this.signInPayload)
  }
  }
 
}
</script>

<template>
  
  <main class="bg-black">
    <input type="text" v-model="signInPayload.mobile">
    <input type="text" v-model="signInPayload.password">

    <button type="button" @click="signIn">click me</button>  
  
  </main>
</template>

<style scoped>

</style>
