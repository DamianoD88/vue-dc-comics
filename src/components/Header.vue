<template>
  <header>
      <a href="#">
          <img src="../../vue-dc-comics-1/img/dc-logo.png" alt="">
      </a>
      <nav>
          <ul>
              <li><a href="#">CHARACTERS</a></li>
              <li><a href="#">COMICS</a></li>
              <li><a href="#">MOVIES</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">GAMES</a></li>
              <li><a href="#">COLLECTIBLES</a></li>
              <li><a href="#">VIDEOS</a></li>
              <li><a href="#">FANS</a></li>
              <li><a href="#">NEWS</a></li>
              <li><a href="#">SHOP</a></li>
          </ul>
      </nav>
    
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

header {
    display: flex;
    justify-content: space-around;
    margin-top: 50px;

    ul {
        list-style: none;
       
        
        
        
        
        
        li {
            display: inline-block;
            font-size: 20px;
            font-weight: bold;
            font-family: "Greta Sans Condensed Bold","Greta Sans Bold",Arial,sans-serif;
            font-size: 20px;
            margin-bottom: 0;
            margin-left: 20px;
            margin-right: 20px;
            padding-bottom: 50px;
            padding-left: 0;
            padding-right: 0;
            padding-top: 0;
            
            
            a {
                text-decoration: none;
                color: #282828;
            }
        }
    }
}

</style>