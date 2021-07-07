<template>
  <header>
      <div class="row">
          <a class="logo" href="#">
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
      </div>
      
      <div class="header-down">
          --> Content goes here
      </div>
    
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

header {

    .row {
        display: flex;
        justify-content: space-around;
        margin-top: 50px;
    }
    

    ul {
        display: flex;
        justify-content: space-around;
        margin-top: 50px;
        list-style: none;
       
        
        
        
        
        
        li {
            display: inline-block;
            font-size: 20px;
            font-weight: bold;
            font-family: "Greta Sans Condensed Bold","Greta Sans Bold",Arial,sans-serif;
            font-size: 10px;
            margin-left: 20px;
            margin-right: 20px;
            padding-bottom: 50px;

            &:hover {
                    color: #0c7cec;
                    border-bottom: 3px solid #0c7cec;
                    transition: all 0.2s
                }
            
            
            a {
                text-decoration: none;
                color: #282828;

                &:hover {
                color: #0c7cec;
                    
                }

                
            }
        }
    }
    .header-down{
        padding-top: 40px;
        padding-left: 12%;
        // margin: 20px, 150px;
        font-size: 25px;
        width: 100%;
        height: 100px;
        background-color: black;
        color: white;
    }
}


</style>