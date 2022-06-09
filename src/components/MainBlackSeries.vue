<template>
    <div class="container_serie">
           <img :src="serieList.thumb">
           <span>{{ serieList.series }}</span>
           <span>Price: {{ serieList.price }}</span>
    </div>
</template>

<script>
export default {
  name: 'SeriesTV',

  props: {
      serieList: Object
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">  
   .container_serie {
       display: flex;
       flex-direction: column;
       margin: 20px;
       flex-basis: 12%;

       img {
           width: 100%;
           height: auto;
       }

       span {
           margin: 5px 0px;
           font-size: 10px;
       }
   } 
</style>