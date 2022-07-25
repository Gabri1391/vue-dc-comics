<template>
        <div class="top-footer">
            <div class="footer-nav">
                <div class="col">
                <ul>
                    <h3>DC Comics</h3>
                    <li v-for="link in links" :key="link.id"><a :href="link.url">{{link.text}}</a></li>
                </ul>
                <ul>
                    <h3>Shop</h3>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop Dc Collectibles</a></li>
                </ul>
            </div>
          <div class="col">
          <ul>
            <h3>DC</h3>
            <li v-for="link in links" :key="link.id"><a :href="link.url">{{link.text}}</a></li>
          </ul>
        </div>
        <div class="col">
          <ul>
            <h3>Sites</h3>
            <li><a href="#">Characthers</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
          </ul>
        </div>

        </div>
            <img src="../assets/img/dc-logo.png" alt="DC logo">
        </div>
</template>

<script>
 export default {
    name: 'TheFooter',
     data(){
        return{
            links:[
  {
    id:1,
    text: 'Characters',
    url: '#',
    current: false,
  },
  {
    id:2,
    text: 'Comics',
    url: '#',
    current: true,
  },
  {
    id:3,
    text: 'Movies',
    url: '#',
    current: false,
  },
  {
    id:4,
    text: 'TV',
    url: '#',
    current: false,
  },
  {
    id:5,
    text: 'Games',
    url: '#',
    current: false,
  },
  {
    id:6,
    text: 'Collectibles',
    url: '#',
    current: false,
  },
  {
    id:7,
    text: 'Videos',
    url: '#',
    current: false,
  },
  {
    id:8,
    text: 'Fans',
    url: '#',
    current: false,
  },
  {
    id:9,
    text: 'News',
    url: '#',
    current: false,
  },
  {
    id:10,
    text: 'Shop',
    url: '#',
    current: false,
  },
]
        }
    }

}
</script>

<style lang="scss" scoped>
    .top-footer{
      height: 500px;
      background-image: url('../assets/img/footer-bg.jpg');
      position: relative;

     img{
         width: 480px;
         position: absolute;
         right: 80px;
         bottom: 10px;
         transform: rotate(-20deg);
     }

    .footer-nav{
        display: flex;
        padding-top: 20px;
    } 

    .col{
        margin: 0 10px;
    }

    h3{
        color: white;
    }

    ul {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
    li a {
      color: gray;
      justify-self: start;
    }

    li a:hover{
        color:wheat;
    }
  }
    
    };

</style>

