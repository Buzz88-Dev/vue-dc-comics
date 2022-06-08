<template>
  <div class="main">
      <div class="title">
          <h1>&#129094; Content goes here &#129092;</h1>
      </div>
  </div>
</template>

<script>
export default {
  name: 'DcMainBlack',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    .main {
        width: 100%;
        background-color: black;
        padding: 50px 0px;
    }

    .title {
        width: 80%;
        margin: auto;
        color: white;
    }

    h1 {
        font-size: 20px;
    }
    
</style>