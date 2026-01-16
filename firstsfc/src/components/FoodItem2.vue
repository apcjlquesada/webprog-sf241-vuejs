<template>
  <div  class="patola"></div>>
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Patola and singkamas',
      message: 'I like santol , durian,patola and singkamas'
    }
  }
};
</script>

<style>
  .patola {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: lightgreen;
  }  
</style>
