<template>
  <header>
    <!-- This is to display the data -->
    <h1>{{title}}</h1>
    <p>{{subTitle}}</p>
  </header>
</template>

<script>
export default {
// Data objects for Vue instance
  data () {
    return {
      title: 'PWA + Vueであそぶよ',
      subTitle: '2つ同時は危険だよ'
    }
  }
}
</script>

<style>
header{
  background-color: #f6f7f9;
  text-align: center;
  padding: 10px;
}
h1{
  color: #013892;
  margin: 0;
}
p{
  color:#999;
  margin: 0;
}
</style>