<template>
  <div class="headposition">
    <div @click.prevent="entrustSelect" class="entrustSelect">
      <p>委托查询</p><img src="../img/向右.png">
    </div>
    <div @click.prevent="tradeSelect" class="tradeSelect">
      <p>成交查询</p><img src="../img/向右.png">
    </div>
    <div @click.prevent="contractSelect" class="contractSelect">
      <p>合同查询s</p><img src="../img/向右.png">
    </div>
  </div>
</template>
<script>
export default {
  data () {
    return {

    }
  },
  methods: {
    entrustSelect(){
      console.log("entrustSelect")
    },
    tradeSelect(){
      console.log("tradeSelect")
    },
    contractSelect(){
      console.log("contractSelect")
    }
  }
}
</script>
<style>
  html{
    height: 100%;
    background-color: rgb(231, 231, 231)
  }
  body{
    margin: 0;
  }
  .headposition{
    width: 100%;
    background-color: white;
  }
  .entrustSelect{
    margin-top: 1rem;
    height: 3rem;
    border-bottom:1px solid rgb(231, 231, 231)
  }
  .entrustSelect p{
    margin: 15px;
    font-size: 17px;
    font-weight: 600;
    position: absolute;
  }
  .entrustSelect img{
    right: 0;
    margin: 15px 5px;
    position: absolute;

  }
  .tradeSelect{
    height: 3rem;
    border-bottom:1px solid rgb(231, 231, 231)
  }
   .tradeSelect p{
    margin: 15px;
    position: absolute;
    font-size: 17px;
    font-weight: 600;
  }
   .tradeSelect img{
    right: 0;
    margin: 15px 5px;
    position: absolute;

  }
  .contractSelect{
    height: 3rem;
    border-bottom:1px solid rgb(231, 231, 231)
  }
   .contractSelect p{
    margin: 15px;
    position: absolute;
    font-size: 17px;
    font-weight: 600;
  }
    .contractSelect img{
    right: 0;
    margin: 15px 5px;
    position: absolute;

  }
</style>
