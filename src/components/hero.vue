<template>
  <div class="image">
    <img src="https://picsum.photos/1000/300" alt="">
    <div class="sub-title">
      <h2>Benvenuto Vue CLI</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'myJumbo',
}
</script>

<style scoped>
  img{
    max-width: 100%;
    max-height: 100%;
    object-fit: cover;
    object-position: center;
  }

  .image{
    position: relative;
  }

  .sub-title{
    widows: 200px;
    height: 100px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    font-size: 25px;
    background-color: rgba(250, 250, 250, 0.8);
    padding: 20px;
    border: 2px solid white;
    border-radius: 10px;
  }
</style>