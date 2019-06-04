<template>
 
<div id="wrap" style="" class="double-submit">
<div id="Wrapper" style="background-color:#3c8dbc;">
	<div class="container">
	<div id="Contents" style="background-color:#ecf0f5;">
	<div class="article" style="background-color:#ecf0f5;">
	<div class="icon"><h2 class="rd25_right"><img src="../assets/image/icon_011.png" alt="">契約商品の登録（入力）</h2></div>
	<div class="lead-desc padb10">
		<p class="mb35">
			契約商品の証券番号を入力いただき、「契約商品を登録する」ボタンを押してください。
		</p>
	</div>
	<div class="section">
	<div class="border01">
		<table class="table01">
		<colgroup>
			<col width="20%">
			<col width="80%">
		</colgroup>
		<tbody>
			<div id="input-form"></div>
			<tr>
			<th>証券番号1</th>
			<td  class="">
			<p class="guide_text">例：0123456789</p>
			<input type="text" name="kkl" maxlength="10" class="type_text w228" placeholder="0123456789" v-model='number'>
			            <p class="bld orange error_icon error_message">
			<span style="display: none;"></span>
			</p>
			</td>
			</tr>
			<tr>
			<th>証券番号2</th>
			<td  class="">
			<p class="guide_text">例：0123456789</p>
			<input type="text" name="jge" maxlength="10" class="type_text w228" placeholder="0123456789" >
			            <p class="bld orange error_icon error_message">
			<span  style="display: none;"></span>
			</p>
			</td>
			</tr>

			<tr>
			<th>証券番号3</th>
			<td  class="">
			<p class="guide_text">例：0123456789</p>
			<input type="text" name="oyu" maxlength="10" class="type_text w228" placeholder="0123456789" >
			            <p class="bld orange error_icon error_message">
			<span  style="display: none;"></span>
			</p>
			</td>
			</tr>

			<tr>
			<th>証券番号4</th>
			<td  class="">
			<p class="guide_text">例：0123456789</p>
			<input type="text" name="def" maxlength="10" class="type_text w228" placeholder="0123456789" >
			            <p class="bld orange error_icon error_message">
			<span  style="display: none;"></span>
			</p>
			</td>
			</tr>

			<tr class="last">
			<th>証券番号5</th>
			<td  class="">
			<p class="guide_text">例：0123456789</p>
			<input type="text" name="abn" maxlength="10" class="type_text w228" placeholder="0123456789" >
			            <p class="bld orange error_icon error_message">
			<span  style="display: none;"></span>
			</p>
			</td>
			</tr>
		</tbody>
		</table>

	</div>
	</div>
	<div id="btn" class="bg_orange rd30 clearfl double-submit" style="background-color:aliceblue;">
		<div class="btn_center wd50p" >
			<a href="javascript:void(0);" @click="dispLoading()" class="BtnNext" style="background-color:#3c8dbc; border-color:#3c8dbc;">証券番号を登録する</a>
		</div>
		<p class="left">
			<router-link  to="/">
			<a href="javascript: void(0);" class="BtnGray"> 戻&nbsp;る</a></router-link>
		</p>
	</div>
</div>
</div>
</div>
</div>
</div></template>

<script>
export default {
	name: 'register',
	data:{
		number : ''
	},
	methods:{
		dispLoading : function(){
			console.log(this.number)
		}
	}
}
</script>


