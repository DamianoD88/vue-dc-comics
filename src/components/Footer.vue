<template>
  <div class="down">
      
      <nav>
          <input type="button" class="button" value="SIGN-UP NOW!">
          <ul>
              <li>FOLLOW US</li>
              <li><img src="../../vue-dc-comics-1\img\footer-facebook.png" alt=""></li>
              <li><img src="../../vue-dc-comics-1\img\footer-periscope.png" alt=""></li>
              <li><img src="../../vue-dc-comics-1\img\footer-pinterest.png" alt=""></li>
              <li><img src="../../vue-dc-comics-1\img\footer-twitter.png" alt=""></li>
              <li><img src="../../vue-dc-comics-1\img\footer-youtube.png" alt=""></li>
              
          </ul>
      </nav>
  </div>
</template>

<script>
export default {
    name: 'down',
    data(){
        return {
            
            
        }
    }
}
</script>

<style lang="scss" scoped>
    .down {
        width: 100%;
        height: 105px;
        background-color: #303030;

        input {
            background: #303030;
            border-color: #0282F9;
            border-style: solid;
            border-width: 2px;
            color: #fff;
            display: inline-block;
            font-size: 20px;
            height: 50px;
            line-height: 45px;
            margin-top: 30px;
            text-align: center;
            text-transform: uppercase;
            transition-duration: .3s;
            transition-property: background-color;
            transition-timing-function: ease;
            width: 150px;
            margin-left: 256px;
        }
        
        ul {
            display: flex;
            justify-content: flex-end;
            list-style: none;
            display: flex;
            align-items: center;
            color: #0282f9;
            margin-right: 285px;
            margin-top: -40px;

            li {
                margin-right: 20px;

                img {
                    width: 25px;
                    height: 25px;
                }
            }

            
        }
    }
</style>
