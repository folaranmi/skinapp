<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="container">
      <div class="box">
        <div class="box_circle"></div>
      </div>

      <div class="box">
        <div class="box_circle"></div>
      </div>

      <div class="box">
        <div class="box_circle"></div>
      </div>

      <div class="box">
        <div class="box_circle"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .container{
    width: 100%;
    height: auto;
    overflow: auto;
    max-width: 1200px;
    margin: 0 auto;
  }
  .box{
    width: 24%;
    height: 300px;
    float: left;
    background: #e7e7e7;
    margin: 20px 0.5%;

    &_circle{
      width: 30px;
      height: 30px;
      border-radius: 50%;
    }
  }
</style>
