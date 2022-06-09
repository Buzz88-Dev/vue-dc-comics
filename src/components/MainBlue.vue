<template>
  <div class="mainBlue">
        <div class="width80">
            <div class="icons">

                <div v-for="(icon, index) in icons" :key="index" class="singleIcon">
                    <img :src="icon.path" alt="">
                    <span>{{ icon.title }}</span>
                </div>

                <!-- struttura icona singola -->
                <!-- <div class="singleIcon">
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </div> -->

            </div>
        </div>
  </div>
</template>

<script>
export default {
  name: 'DcMainBlue',

  data(){
    return {
      icons : [       
        {
          title : "DIGITAL COMICS",
          path : require('../assets/buy-comics-digital-comics.png'),
        },

        {
          title : "DC MERCHANDISE",
          path : require('../assets/buy-comics-merchandise.png'),
        },

        {
          title : "SUBSCRIPTION",
          path : require('../assets/buy-comics-subscriptions.png'),
        },

        {
          title : "COMIC SHOP LOCATOR",
          path : require('../assets/buy-comics-shop-locator.png'),
        },

        {
          title : "DC POWER VISA",
          path : require('../assets/buy-dc-power-visa.svg'),
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
        padding: 40px 20px;
    }

    .singleIcon img {
        width: 20%;
        height: auto;
    }

    .singleIcon span {
        font-size: 10px;
        margin-left: 8px;
    }

</style>