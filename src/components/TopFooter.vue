<template>
  <div id="wrapper">
    <div class="container">
      <nav>
        <ul>
          <h4>DC COMICS</h4>
          <li v-for="(link, index) in NavLinks1" :key="index">
            <a href="#">{{link.text}}</a>
          </li>
        </ul>
        <ul>
          <h4>SHOP</h4>
          <li v-for="(link, index) in NavLinks2" :key="index">
            <a href="#">{{link.text}}</a>
          </li>
        </ul>
        <ul>
          <h4>DC</h4>
          <li v-for="(link, index) in NavLinks3" :key="index">
            <a href="#">{{link.text}}</a>
          </li>
        </ul>
        <ul>
          <h4>SITES</h4>
          <li v-for="(link, index) in NavLinks3" :key="index">
            <a href="#">{{link.text}}</a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexTopFooter',
  data: function () {
    return {
      NavLinks1: [
        {
          text: 'Characters',
          url: '#'
        },
        {
          text: 'Comics',
          url: '#'
        },
        {
          text: 'Movies',
          url: '#'
        },
        {
          text: 'Tv',
          url: '#'
        },
        {
          text: 'Games',
          url: '#'
        },
        {
          text: 'Videos',
          url: '#'
        },
        {
          text: 'News',
          url: '#'
        }
      ],
      NavLinks2: [
        {
          text: 'Shop DC',
          url: '#'
        },
        {
          text: 'Shop DC Collectibles',
          url: '#'
        }
      ],
      NavLinks3: [
        {
          text: 'Terms Of Use',
          url: '#'
        },
        {
          text: 'Privacy policy (New)',
          url: '#'
        },
        {
          text: 'Ad Choices',
          url: '#'
        },
        {
          text: 'Advertising',
          url: '#'
        },
        {
          text: 'Jobs',
          url: '#'
        },
        {
          text: 'Subscriptions',
          url: '#'
        },
        {
          text: 'Talent Workshops',
          url: '#'
        },
        {
          text: 'CPSC Certificates',
          url: '#'
        },
        {
          text: 'Ratings',
          url: '#'
        },
        {
          text: 'Shop Help',
          url: '#'
        },
        {
          text: 'Contact Us',
          url: '#'
        }
      ],
      NavLinks4: [
        {
          text: 'DC',
          url: '#'
        },
        {
          text: 'MAD Magazine',
          url: '#'
        },
        {
          text: 'DC Kids',
          url: '#'
        },
        {
          text: 'DC Universe',
          url: '#'
        },
        {
          text: 'DC Power Visa',
          url: '#'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
#wrapper{
    width: 100%;
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
    height: 375px;
    .container{
      margin: 0 auto;
      width: 67%;
      height: 100%;
      display: flex;
      justify-content: space-between;
      background-image: url('../assets/img/dc-logo-bg.png');
      background-repeat: no-repeat;
      background-position-x: right;
      background-position-y: -6rem;
    }
    nav{
      display: flex;
      gap: 50px;
      margin-top: 30px;
      h4{
        color: white;
      }
      li{
      list-style: none;
      a{
        text-decoration: none;
        color: grey;
        &:hover{
          color: rgb(0, 123, 255);
        }
      }
    }
    }
}
</style>
