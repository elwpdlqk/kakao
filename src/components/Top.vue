<template>
    <div class="top">
        <div class="nav">
            <div class="left--box navbox">
                <span>채팅</span>
            </div>
            <div class="right--box navbox">
                <div class="icon"></div>
                <div class="icon"></div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
}
</script>

<style>
  .top {
    height: 50px;
    background: #755258;
    color: #fff;
  }

  .nav {
      position: relative;
      height: 50px;
  }
  .navbox {
      position: absolute;
      top: 50%;
      transform: translate(0,-50%)
  }
  .left--box {
      left: 10px;
      font-size: 1.5em;
  }
  .right--box {
      right: 10px;
  }
    .icon {
      width: 20px;
      height: 20px;
      background-color: #000;
      float: left;
      margin-left: 10px;
  }
</style>
