<template>
  <div class="hello">
    <div class="talk_content">
    </div>
    <div class="btn_content">
    </div>
  </div>
</template>

<script>
export default {
}
</script>
<style>
.talk_content{
  width:100%;
  height: 90%;
  background:blue;
  position: absolute;
  top:0;
  left:0;
  overflow: scroll;
}
.btn_content{
  width:100%;
  height: 10%;
  background: red;
  position: absolute;
  top:90%;
  left:0;
}
</style>
