<template>
  <div class="background_Image">
      <div class="width80">
            <div class="text_left">

                <div class="text_column" v-for="(servizio, index) in services" :key="index">
                    <h4>{{ servizio.title }}</h4>
                    <span v-for="(nameService, i) in servizio.service" :key="i"> {{ nameService }}</span>
                </div>
            </div>

            <div class="image_right">
                
            </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'DcFooter',

  data(){
      return {
          services : [
            {
                title: "DC COMICS",
                service : ["Characters", "Comics", "Movies", "TV", "Games", "Videos", "News"]
            },

            {
                title: "SHOP",
                service : ["Shop DC", "Shop DC Collectibles"]
            },

            {
                title: "DC",
                service : ["Terms Of Use", "Privacy policy (New)", "Ad Choices", "Advertising", "Jobs", "Subscriptions", "Talent Workshops", "CPSC Certificates", "Ratings", "Shop Help", "Contact Us"]
            },

            {
                title: "SITES",
                service : ["DC", "MAD Magazine", "Ad Choices", "DC Kids", "DC Universe", "DC Power Visa"]
            }

        ]   
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

    .background_Image {
        background-image: url("../assets/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
    }

    .width80 {
        width: 80%;
        margin: auto;
        display: flex;
        justify-content: space-between;
    }

    .text_left {
        display: flex;
        width: 40%;
        padding: 40px 0px;
    }

    .text_column {
        display: flex;
        flex-direction: column;
        width: 25%;
        margin-right: 10px;
    }

    h4 {
        color: white;
        font-size: 12px;
    }

    span {
        font-size: 9px;
        color: rgb(169, 165, 165);
        margin-top: 5px;
    }

    .image_right {
        background-image: url('../assets/dc-logo-bg.png');
        background-repeat: no-repeat;
        background-position: center;
        background-size: 80% 130%;
        width: 50%;
    }

</style>