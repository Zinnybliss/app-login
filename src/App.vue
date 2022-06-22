<template>
  <div id="app">
    <router-view/>
  
  </div>
</template>



<script>
import axios from 'axios'
export default {
  name: 'mainApp',
  created (){
    this.getData()
  },
  data(){
    return{
      chelseaFan: '',
    }
  },
  methods: {
    getData (){
      axios.get('http://localhost:3000/account')
      .then(res => {console.log(res.data)
      this.chelseaFan = res.data.name
      })

    }
  }
}
</script>


<style>
html{
        scroll-behavior: smooth;
      }
</style>
