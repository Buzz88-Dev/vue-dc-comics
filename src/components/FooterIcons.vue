<template>
  <div class="footer_backgr">
        <div class="width80">
            <div class="myButton">
                <button>SIGN-UP NOW!</button>
            </div>

            <div class="icons">
                <div>
                    <span>FOLLOW US</span>
                </div>

                <div>
                    <img src="../assets/footer-facebook.png" alt="">
                </div>

                <div>
                    <img src="../assets/footer-twitter.png" alt="">
                </div>

                <div>
                    <img src="../assets/footer-youtube.png" alt="">
                </div>

                <div>
                    <img src="../assets/footer-pinterest.png" alt="">
                </div>

                <div>
                    <img src="../assets/footer-periscope.png" alt="">
                </div>

            </div>      
        </div>    
  </div>
</template>

<script>
export default {
  name: 'FooterIcons',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    .footer_backgr {
        width: 100%;
        background-color: rgb(53, 51, 51);
    }

    .width80 {
        width: 80%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 30px 0px;
    }

    button {
        color: white;
        background-color: rgb(53, 51, 51);
        padding: 10px;
        border: rgb(31, 75, 235) 2px solid;
    }
    .icons {
        display: flex;
        align-items: center;

        span {
            font-size: 15px;
            color: rgb(59, 59, 238);
        }

        img {
            margin-left: 10px;
            border-radius: 50%;
            background-color: rgb(53, 51, 51);
        }
    }


</style>