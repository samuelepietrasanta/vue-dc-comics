<template>
  <footer>
      <div id="info">
          <div class="column">
            <div>
                <h4>dc comics</h4>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>

                </ul>

            </div>

            <div>
                <h4>shop</h4>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC collectibles</li>
                </ul>

            </div>

          </div>

          <div>
            <h4>dc</h4>
            <ul>
                <li>Terms Of Use</li>
                <li>Privacy policy (New)</li>
                <li>Ad Choises</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscription</li>
                <li>Talent Workshop</li>
                <li>CPSC Certificate</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>

            </ul>

          </div>

          <div>
          <h4>sites</h4>
          <ul>
              <li>DC</li>
              <li>MAD Magazine</li>
              <li>DC Kids</li>
              <li>DC Universe</li>
              <li>DC Power Visa</li>


          </ul>

          </div>

          <div id="logo-footer">
              <img src="../img/dc-logo-bg.png" alt="logo dc">
          </div>

        
        



      </div>
      <div id="social-sign-up"></div>
  </footer>
</template>

<script>
export default {
    name:'Footer'

}
</script>

<style scoped lang="scss">
footer{
    height: 350px;
    padding:30px 200px;
    background-image: url(../img/footer-bg.jpg);

    #info{
        display: flex;
        .column{
            margin: 0 20px;
        }

        ul{
            list-style: none;
            li{
                padding-left:15px;
                font-size: 0.8rem;
                color:rgb(124, 124, 124);
                padding-top:5px;
            }
        };
        h4{
            padding: 15px;
            color:white;
            text-transform: uppercase;
        }
    }
}

#logo-footer img{
    height: 300px;
    margin-left:200px;  //# so che questa implementazione è sbagliata , la rifaccio nel weekend
}

</style>