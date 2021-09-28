<template>
  <div id="body">
      <div id="card-container">
        <Card v-for="(game, index) in games" :key='index' :source="game.thumb" :tipo="game.type"/>

      </div>
  </div>
</template>

<script>
import Card from './Card.vue';
import database from '../data/comics.js'

export default {
    name : 'Body',
    data: function(){
        return{
            games : database,
        }
    },
    components : {
        Card,
    }

}
</script>

<style scoped lang="scss">


#body{
    background-color: rgb(29, 23, 23);
    padding:15px;

    #card-container{
    display: flex;
    width:70%;
    margin:0 auto;
    flex-wrap: wrap;
    }

}


</style>