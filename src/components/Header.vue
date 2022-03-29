<template>
  <div id="header">
    <div id="nav-container">
      <a href="#">
        <img src="../assets/img/dc-logo.png" alt="" />
      </a>
      <nav>
        <ul>
          <li v-for="(link, index) in HeaderLinks" :key="index" :class="{active: link.current}">
            <a :class="{ active: link.current }" href="#">{{ link.text }}</a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexHeader',
  data: function () {
    return {
      HeaderLinks: [
        {
          text: 'CHARACTERS',
          url: '#',
          current: false
        },
        {
          text: 'COMICS',
          url: '#',
          current: true
        },
        {
          text: 'MOVIES',
          url: '#',
          current: false
        },
        {
          text: 'TV',
          url: '#',
          current: false
        },
        {
          text: 'GAMES',
          url: '#',
          current: false
        },
        {
          text: 'COLLECTIBLES',
          url: '#',
          current: false
        },
        {
          text: 'VIDEO',
          url: '#',
          current: false
        },
        {
          text: 'FANS',
          url: '#',
          current: false
        },
        {
          text: 'NEWS',
          url: '#',
          current: false
        },
        {
          text: 'SHOP',
          url: '#',
          current: false
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
#header {
  width: 100%;
  height: 115px;
  #nav-container {
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    width: 67%;
    height: 100%;
    background-color: white;
    img {
      padding: 20px;
      width: 7.40rem;
    }
  }
}
ul {
  height: 100%;
  display: flex;
  gap: 30px;
  align-items: center;
  li {
    list-style-type: none;
    height: 100%;
    line-height: 115px;
    &:hover {
      border-bottom: 4px solid #0282f9;
    }
    &.active{
        border-bottom: 4px solid #0282f9;
        color: #0282f9;
      }
    a {
      text-decoration: none;
      color: black;
      font-weight: 900;
      &:hover {
        color: #0282f9;
      }
      &:active,
      &.active{
        color: #0282f9;
      }
    }
  }
}
</style>
