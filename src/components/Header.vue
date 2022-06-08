<template>
  <div class="header">
    <nav class="navbar">

      <div class="image">
        <img src="../assets/dc-logo.png">
      </div>


      <ul>
          <li>
              <a href="#">CHARACTERS</a>
          </li>
          <li>
              <a href="#">COMICS</a>
          </li>
          <li>
              <a href="#">MOVIES</a>
          </li>
          <li>
              <a href="#">TV</a>
          </li>
          <li>
              <a href="#">GAMES</a>
          </li>
          <li>
              <a href="#">COLLECTIBLES</a>
          </li>
          <li>
              <a href="#">VIDEOS</a>
          </li>
          <li>
              <a href="#">FANS</a>
          </li>
          <li>
              <a href="#">NEWS</a>
          </li>
          <li>
              <a href="#">SHOP</a>
          </li>
      </ul>
    </nav>  

  </div>
</template>

<script>
export default {
  name: 'DcHeader',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

  .header {
    width: 80%;
    margin: auto;
  }
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    // Debug
    background-color: red;
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
