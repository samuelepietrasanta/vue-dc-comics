<template>
  <div id="card">
      <img :src="source" alt='immagine comic'>
      <h5>{{tipo}}</h5>
  </div>
</template>

<script>
export default {
    name:'Card',
    props : ['source', 'tipo'],

}
</script>

<style lang="scss" scoped>

#card{
    height: 180px;
    width:150px;
    margin: 5px;

    img{
        height: 85%;
        width: 100%;
        object-fit: cover;
        object-position: top;
    }

    h5{
        margin-top: 4px;
        text-transform: uppercase;
        color:white;
    }
}

</style>