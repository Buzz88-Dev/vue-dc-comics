<template>
  <div class="mainBlue">
        <div class="width80">
            <div class="icons">
                <div class="singleIcon">
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </div>

                <div class="singleIcon">
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </div>
        
                <div class="singleIcon">
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCRIPTION</span>
                </div>

                <div class="singleIcon">
                    <img src="../assets/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </div>

                <div class="singleIcon">
                    <img src="../assets/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
                </div>
            </div>
        </div>
  </div>
</template>

<script>
export default {
  name: 'DcMainBlue',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    .mainBlue {
        width: 100%;
        background-color: rgb(28, 133, 198);
        color: white;
    }

    .width80 {
        width: 80%;
        margin: auto;
    }

    .icons {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .singleIcon {
        width: 20%;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 20px 20px;
    }

    .singleIcon img {
        width: 25%;
        height: auto;
    }

    .singleIcon span {
        font-size: 10px;
        margin-left: 8px;
    }

</style>