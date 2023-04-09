<script>
export default {
  data(){
    return{
      title: "This is My Title for Monday",
      person: {
        id: 5,
        name: 'Bill',
        img: "https://www.buscabiografias.com/img/people/Bill_Murray.jpg" 
      },
      msg: "Bill uno de los integrantes de los cazafantasmas",
    }
  },
};
</script>

<template>
  <h3>{{ title }}</h3>
  <!-- <div id="person"> -->
  <div :id="person.id">
    <h4>{{ person.name }}</h4>
    <img :src="person.img" :alt="person.name">
    <!-- <img v-bind:src="person.img" :alt="person.name"> -->
  </div>
  <h5>{{ msg }}</h5>
  <!-- <h5 v-html="msg"></h5> -->
  <!-- v-html es una directiva -->
</template>

<style lang="css" scoped>
h3{
  color: magenta;
}
</style>