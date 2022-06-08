<template>
  <div class="background_Image">
      <div class="width80">
            <div class="text_left">
                <div class="text_column">
                    <h4>DC COMICS</h4>
                    <span>Characters</span>
                    <span>Comics</span>
                    <span>Movies</span>
                    <span>TV</span>
                    <span>Games</span>
                    <span>Videos</span>
                    <span>News</span>
                </div>

                <div class="text_column">
                    <h4>SHOP</h4>
                    <span>Shop DC</span>
                    <span>Shop DC Collectibles</span>
                </div>

                <div class="text_column">
                    <h4>DC</h4>
                    <span>Terms Of Use</span>
                    <span>Privacy policy (New)</span>
                    <span>Ad Choices</span>
                    <span>Advertising</span>
                    <span>Jobs</span>
                    <span>Subscriptions</span>
                    <span>Talent Workshops</span>
                    <span>CPSC Certificates</span>
                    <span>Ratings</span>
                    <span>Shop Help</span>
                    <span>Contact Us</span>
                </div>

                <div class="text_column"> 
                    <h4>SITES</h4>
                    <span>DC</span>
                    <span>MAD Magazine</span>
                    <span>DC Kids</span>
                    <span>DC Universe</span>
                    <span>DC Power VIsa</span>
                </div>
            </div>

            <div class="image_right">
                <img src="../assets/dc-logo-bg.png" alt="">
            </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'DcFooter',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    .background_Image {
        background-image: url("../assets/footer-bg.jpg");
        // debug
        height: 300px;
    }

    .width80 {
        width: 80%;
        margin: auto;
        display: flex;
    }

    .text_left {
        display: flex;
        justify-content: flex-start;
    }

    .text_column {
        display: flex;
        flex-direction: column;
    }

    h4 {
        color: white;
    }

    span {
        font-size: 9px;
        color: rgb(169, 165, 165);
    }

    .image_right {
        text-align: right;
    }
    .image_right img {
        width: 40%;
        height: auto;
    }
</style>