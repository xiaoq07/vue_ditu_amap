<template>
 <!--a class="link" v-link="{name: 'hi'}">跳转到hi</a-->	
 <div class='searchbox'>
 	<div class='searchbox-container'><input class='sole_input' type="text"><div class='input_close'></div></div>

 </div>
 <button class='search-button'></button>
</template>
<script>
</script>
<style>
.searchbox{
	position: relative;
    z-index: 2;
    pointer-events: auto;
    width: 368px;
    float: left;
    box-sizing: border-box;
    box-shadow: 1px 2px 1px rgba(0,0,0,.15);
}
.searchbox-container{
	position: relative;
    z-index: 2;
    pointer-events: auto;
    width: 368px;
    float: left;
    box-sizing: border-box;
    box-shadow: 1px 2px 1px rgba(0,0,0,.15);
}
.sole_input{
	box-sizing: border-box;
    border: 0;
    padding: 9px 0;
    border-left: 10px solid transparent;
    border-right: 27px solid transparent;
    line-height: 20px;
    font-size: 16px;
    height: 38px;
    color: #333;
    position: relative;
    border-radius: 2px 0 0 2px;
        float: left;
    width: 329px;
}
.search-button{
	    pointer-events: auto;
    background: url(http://webmap0.map.bdstatic.com/wolfman/static/common/images/new/searchbox_f175577.png) no-repeat 0 -76px #3385ff;
    width: 57px;
    height: 38px;
    float: left;
    border: 0;
    padding: 0;
    cursor: pointer;
    border-radius: 0 2px 2px 0;
    box-shadow: 1px 2px 1px rgba(0,0,0,.15);
}
.input_close{
	box-sizing: border-box;
    float: left;
    height: 38px;
    width: 39px;
    cursor: pointer;
    position: relative;
        background: url(http://webmap0.map.bdstatic.com/wolfman/static/common/images/new/searchbox_f175577.png) no-repeat 0 0;
}
.input_close:before {
    content: '';
    position: absolute;
    width: 38px;
    left: 0;
    top: 6px;
    height: 26px;
    border-left: 1px solid #eee;
}

</style>