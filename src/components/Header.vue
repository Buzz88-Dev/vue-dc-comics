<template>
  <div class="dcHeader">
    <nav class="dcNavbar">
      <div class="image">
        <img src="../assets/dc-logo.png">
      </div>


      <ul>
          <li v-for="(link, index) in links" :key="index">
              <a :href="link.url">{{ link.text }}</a>
          </li>
      </ul>
    </nav>  

  </div>
</template>

<script>
export default {
  name: 'DcHeader',

  data(){
    return {
      links : [       
        {
          text : "CHARACTERS",
          url : "#",
          cursor : false,
        },

        {
          text : "COMICS",
          url : "#",
          cursor : false,
        },

        {
          text : "MOVIES",
          url : "#",
          cursor : false,
        },

        {
          text : "TV",
          url : "#",
          cursor : false,
        },

        {
          text : "GAMES",
          url : "#",
          cursor : false,
        },

        {
          text : "TV",
          url : "#",
          cursor : false,
        },

        {
          text : "COLLECTIBLES",
          url : "#",
          cursor : false,
        },

        {
          text : "VIDEOS",
          url : "#",
          cursor : false,
        },

        {
          text : "FANS",
          url : "#",
          cursor : false,
        },

        {
          text : "NEWS",
          url : "#",
          cursor : false,
        },

        {
          text : "SHOP",
          url : "#",
          cursor : false,
        },
      ],
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

  * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
  }

  .dcHeader {
    width: 100%;
  }
  .dcNavbar {
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .image img {
    width: 60%;
    height: auto;
    padding: 15px 0px;
  }

  ul {
    list-style-type: none;

    li {
      display: inline-block;
      font-size: 11px;

      a {
        text-decoration: none;
        color: black;
        margin-left: 20px;

        &:hover {
          color: rgb(28, 133, 198);
        }
      }
    }
  }
</style>
