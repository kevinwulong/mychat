<template>
  <div class="hello">
     <div class="main_content">
                <ul>
                       <li class="item_box" v-for="item in items" >
                              <p>{{item}}</p>
                       </li>
                </ul>
     </div>
     <div class="btn_content">
        <button>{{opOne}}</button>
        <button>{{opTwo}}</button>
     </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
        items:  ['喂、喂、听得到吗！'],
        opOne: '听得到！你是谁！',
        opTwo: '2'
    }
  }
}
</script>
<style >
.main_content{
  width:100%;
  height: 90%;
  background: rgb(43, 45, 66);
  position: absolute;
  top:0;
  left:0;
  overflow: scroll;
}
.btn_content{
  width:100%;
  height:10%;
  background: rgb(0, 52, 89);
  position: absolute;
  top:90%;
  left:0;
}
.item_box{
  list-style: none;
  width:90%;
  min-height: 120px;
  margin:5% auto 7% auto;
  border:1px solid rgba(141, 153, 174, 0.8);
  border-radius: 15px;
  background: rgba(43, 45, 66,0.8);
}
.item_box>p{
  font-size: "微软雅黑";
  font-weight: 0;
  color:rgb(141, 153, 174);
  font-size: 50px;
  text-align: left;
  width:95%;
  margin:20px auto;
}
.btn_content>button{
  float: left;
  width:40%;
  height: 80%;
  margin:20px 5% ;
  background: #fff;
  border:none;
  border-radius: 10px;
  font-size: 35px;
  color:rgb(141, 153, 174);
  overflow: hidden;
}
</style>
