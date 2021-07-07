<template>
  <section class="products">
      <nav>
          <ul>
              <div class="title">DC COMICS</div> 

              <li v-for="(link,index) in links1" :key="index" :class="link.current ? 'active' : '' "><a :href="link.url"> {{ link.text }} </a></li>
          </ul> 
          <ul>
              <div class="title">SHOP</div>
              <li v-for="(link,index) in links2" :key="index" :class="link.current ? 'active' : '' "><a :href="link.url"> {{ link.text }} </a></li>
          </ul>
          <ul>
              <div class="title">DC</div>
              <li v-for="(link,index) in links3" :key="index" :class="link.current ? 'active' : '' "><a :href="link.url"> {{ link.text }} </a></li>
          </ul>
          <ul>
              <div class="title">SITES</div>
              
              <li v-for="(link,index) in links4" :key="index" :class="link.current ? 'active' : '' "><a :href="link.url"> {{ link.text }} </a></li>
          </ul>
          <ul>
              <li>
                  <img src="../../vue-dc-comics-1/img/dc-logo-bg.png" alt="">
              </li>
          </ul>
      </nav>
      
  </section>
</template>

<script>
export default {
    name: 'products',
    data(){
        return {
            links1: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: false
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false
                },
                {
                    text: 'News',
                    url: '#',
                    current: false
                },
            ],
            links2: [
                {
                    text: 'Shop DC',
                    url: '#',
                    current: false
                },
                {
                    text: 'Shop DC Collectibles',
                    url: '#',
                    current: false
                },
            ],
            links3: [
                {
                    text: 'Terms Of Use',
                    url: '#',
                    current: false
                },
                {
                    text: 'Privacy Policy (New)',
                    url: '#',
                    current: false
                },
                {
                    text: 'Advertising',
                    url: '#',
                    current: false
                },
                {
                    text: 'Jobs',
                    url: '#',
                    current: false
                },
                {
                    text: 'Subscriptions',
                    url: '#',
                    current: false
                },
                {
                    text: 'CPSC Certificates',
                    url: '#',
                    current: false
                },
                {
                    text: 'Ratings',
                    url: '#',
                    current: false
                },
                {
                    text: 'Shop Help',
                    url: '#',
                    current: false
                },
                {
                    text: 'Contact Us',
                    url: '#',
                    current: false
                },
            ],
            links4: [
                {
                    text: 'DC',
                    url: '#',
                    current: false
                },
                {
                    text: 'DC UNIVERSE INFINITE',
                    url: '#',
                    current: false
                },
                {
                    text: 'DC Kids',
                    url: '#',
                    current: false
                },
                {
                    text: 'DC Shop',
                    url: '#',
                    current: false
                },
                {
                    text: 'MAD Magazine',
                    url: '#',
                    current: false
                },
            ],

        }
    }

}
</script>

<style lang="scss" scoped>

    .products {
        background-image: url(../../vue-dc-comics-1/img/footer-bg.jpg);
        height: 400px;

        .title {
            margin-bottom: 20px;
        }

        nav {
            display: flex;
            flex-wrap: wrap;
            padding-left: 250px;
            padding-top: 50px;

            ul {
                padding-right: 50px;
                color:white;
                list-style: none;
                font-size: 12px;

                li {
                    margin-bottom: 10px;
                    color: lightgrey;

                    a {
                        text-decoration: none;
                        color: #767070;

                        &:hover
                        &:active {
                        color: #0c7cec;
                            
                        }
                    }
                    img {
                       margin-top: -153px; 
                    }
                }
            }
            
        }
        
    }

</style>