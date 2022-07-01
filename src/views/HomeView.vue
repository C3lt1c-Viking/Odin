<template>
  <div class="home" style="margin: 0 auto; text-align: center; float: center">
    <img alt="Vue logo" src="../assets/logo.png">   <img alt="Odin" src="../assets/odin.jpg" height="200" width="200">
    <HelloWorld msg="Welcome to Odin! A site built on VueJS!"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

export default defineComponent({
  name: 'HomeView',
  components: {
    HelloWorld
  }
})
</script>
