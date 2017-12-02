<template>
  <footer>
    <!-- This is to display the data-->
    <p>{{addr}}</p>
    <p>{{copyright}}</p>
  </footer>
</template>

<script>
export default {
  // Data objects for Vue instance
  data () {
    return {
      addr: 'Ogikubo Suginamiku Tokyo',
      copyright: 'Hanasoo Inc. All rights reserved.'
    }
  }
}
</script>

<style>
footer{
  background-color: #c9c9c9;
  text-align: center;
}
h1{
  color: #013892;
  margin: 0;
}
p{
  color:#000;
  margin: 0;
}
</style>