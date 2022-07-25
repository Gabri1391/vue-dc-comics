<template>
    <div class="bottom-footer">
        <a href="#" class="btn"><h3>SIGN UP NOW!</h3></a>
        <div class="social">
          <h2>FOLLOW US</h2>
          <a href="#"
            ><img src="../assets/img/footer-facebook.png" alt="facebook"
          /></a>
          <a href="#"
            ><img src="../assets/img/footer-twitter.png" alt="facebook"
          /></a>
          <a href="#"
            ><img src="../assets/img/footer-youtube.png" alt="facebook"
          /></a>
          <a href="#"
            ><img src="../assets/img/footer-pinterest.png" alt="facebook"
          /></a>
          <a href="#">
            <img src="../assets/img/footer-periscope.png" alt="facebook" />
          </a>
        </div>  
    </div>
</template>

<script>
 export default {
    name:'BottomFooter'
 }
</script>

<style lang="scss" scoped>
  .bottom-footer {
    background-color: #303030;
    padding: 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .social {
      display: flex;
      align-items: center;
    }

    h2 {
        color: #0282f9;
        margin-right: 20px;
        font-size: 1.2rem;
    }

    img{
      margin: 0 10px;
    }

    .btn{
      padding: 0 10px;
      border: 3px solid #0282f9;
    }

    .btn h3{
      color: white;
    }

  };


</style>