<template>
  <div id="wrapper">
      <div class="container">
          <button>SIGN-UP NOW!</button>
          <nav>
              <h2>FOLLOW US</h2>
              <img src="../assets/img/footer-facebook.png" alt="">
              <img src="../assets/img/footer-twitter.png" alt="">
              <img src="../assets/img/footer-youtube.png" alt="">
              <img src="../assets/img/footer-pinterest.png" alt="">
              <img src="../assets/img/footer-periscope.png" alt="">
          </nav>
      </div>
  </div>
</template>

<script>
export default {
  name: 'BottomFooter'
}
</script>

<style lang="scss" scoped>
#wrapper{
    width: 100%;
    height: 110px;
    background-color: #303030;
    .container{
        margin: 0 auto;
        width: 67%;
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        button{
            border: 2px solid rgb(0, 123, 255);
            background-color: #303030;
            padding: 15px;
            color: white;
            font-size: 1.10rem;
            height: 50px;
        }
        nav{
            display: flex;
            gap: 20px;
            h2{
                color: rgb(0, 123, 255);
            }
        }
    }
}
</style>
