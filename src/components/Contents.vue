<template>
  <div id="wrapper">
      <div class="contents-container">
          <h1>Content goes here</h1>
      </div>
  </div>
</template>

<script>
export default {
  name: 'IndexContents'
}
</script>

<style lang="scss" scoped>
#wrapper{
    width: 100%;
    height: 115px;
    background-color: #1c1c1c;
    .contents-container{
        width: 67%;
        height: 100%;
        margin: 0 auto;
        display: flex;
        align-items: center;
        h1{
            color: white;
        }
    }
}
</style>
