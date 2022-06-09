<template>
    <div class="container">
        <div >
           <img :src="serieList.thumb">
           <span>{{ serieList.series }}</span>
           <span>Price: {{ serieList.price }}</span>
       </div>
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
        width: 150px;
        padding: 20px 0px;

        img {
            width: 150px;
            height: 150px;
        }
    }

    span {
        font-size: 10px;
        padding: 5px 0px;
    }
</style>