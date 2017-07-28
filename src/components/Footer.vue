<template>
  <footer>
  <p>{{copyright}}</p>
  </footer>
</template>

<script>
export default {
  data: function(){
    return{
      copyright: 'Copyright 2017 vuejs'
    }
  }
}
</script>

<style scoped>
  footer {
    background: #222;
    padding: 6px;
  }

  p{
    text-align: center;
    background-color: white;
  }

</style>
