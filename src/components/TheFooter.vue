<template>
        <div class="top-footer">
            <div class="footer-nav">
                <div class="col">
                <ul>
                    <h3>DC Comics</h3>
                    <li><a href="#">Characthers</a></li>
                    <li><a class="active" href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Collectibles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
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
            <li><a href="#">Characthers</a></li>
            <li><a class="active" href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Collectibles</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">Fans</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Shop</a></li>
          </ul>
        </div>
        <div class="col">
          <ul>
            <h3>Sites</h3>
            <li><a href="#">Characthers</a></li>
            <li><a class="active" href="#">Comics</a></li>
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
    name: 'TheFooter'

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

