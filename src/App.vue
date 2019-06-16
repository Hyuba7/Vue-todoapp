<template>
  <div id="app">
    
  </div>
</template>

<script>
import Todos from './components/Todos'


export default {
  name: 'app',
  components: {
    
  },
  data () {
    return {
      todos: [
     {
       id: 1,
       titile: "Todo One",
       completed: false
     },
     {
       id: 2,
       titile: "Todo Two",
       completed: true
     },
     {
       id: 3,
       titile: "Todo Three",
       completed: false
     }
      ]

    }
    
  }

}
</script>


<style>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

  body{
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1,4;
  }
</style>
