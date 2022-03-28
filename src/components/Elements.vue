<template>
  <div id="wrapper">
    <div class="elements-container">
        <div class="container">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <span>DIGITAL COMICS</span>
        </div>
        <div class="container">
            <img src="../assets/img/buy-comics-merchandise.png" alt="">
            <span>DC MERCHANDISE</span>
        </div>
        <div class="container">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            <span>SUBSCRIPTION</span>
        </div>
        <div class="container">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            <span>COMIC SHOP LOCATOR</span>
        </div>
        <div class="container">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
            <span>DC POWER VISA</span>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexElements'
}
</script>

<style lang="scss" scoped>
#wrapper {
  width: 100%;
  height: 150px;
  padding: 30px;
  background-color: #0282f9;
  .elements-container {
    margin: 0 auto;
    width: 67%;
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: white;
    .container{
        img{
        width: 50px;
        margin-right: 19px;
        vertical-align: middle;
    }
        span{
            font-size: 0.9rem;
        }
    }
  }
}
</style>
