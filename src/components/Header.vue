<template>
  <header>
      <nav>
          <img src="../img/dc-logo.png" alt="Dc logo">
          <ul>
              <li v-for="(element, index) in elements" :key=index> {{element}}</li>

          </ul>
      </nav>

  </header>
</template>

<script>
export default {
    name: 'Header',

    data: function(){
        return{

            elements:[
                'characters',
                'comics',
                'movies',
                'tv',
                'games',
                'collectibles',
                'videos',
                'fans',
                'news',
                'shop'
            ]
        }
    }

}
</script>

<style scoped lang="scss">

nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 80px;
    margin-bottom:15px;
    img{
        height: 100%;
    }
    ul{
        display: flex;
        list-style: none;
        li{
            text-transform: uppercase;
            font-size:0.8rem;
            padding:0 8px;
            color:rgb(90, 90, 90);
        }
    }
}

.active{
    color:rgb(0, 162, 255);
}

</style>