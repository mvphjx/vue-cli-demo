<template>
   <div>
   	 <img id="code" src="../img/code.png">
   	 <div id="note" v-once>{{msg}}<div id="h"></div></div>

   </div>

</template>

<script>
export default {
  data () {
    return {
      msg: 'vue.js正式入门'
    }
  }
}
</script>

<style >
#code{
	width: 80%;
	margin:10px 10%;

}
#note{
	width: 80%;
	line-height: 35px;
	margin: 10px auto;

}
 #h{
 	width: 100%;
 	height: 60px;
 }
</style>
