<template>
    <header>
        <figure>
            <img src="../assets/img/dc-logo.png" alt="DC logo">
        </figure>
        <ul>
          <li v-for="link in links" :key="link.id" >
          <a :class="{active: link.current}" :href="link.url">
          {{link.text}}</a>
          </li>
        </ul>
    </header>
</template>

<script>
 export default {
    name: 'BaseHeader',
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
 header{
    display: flex;
    justify-content: space-between;
    align-items: center;
 }

img{
    width: 80px;
    padding-right: 30px;
}

 ul{
    display: flex;
    justify-content: center;
    padding-right: 120px;
    margin: 10px;
 }

 li{
    padding: 10px;
 }

  a{
    color: black;
    font-weight: bold;
    font-size: 0.8rem;
    padding: 10px;
  }

  a.active{
    border-bottom: 1px solid blue;
  }

</style>