<template>
<body>

<div id="loading" data-bind="visible: false" style="display: none;">
	<div class="contents" style="text-align: center;">
		しばらくお待ちください…
	</div>
</div>

<div id="wrap" style="" class="double-submit">
<div id="Wrapper" style="background-color:#3c8dbc;">
<div class="container">
<div id="Contents" style="background-color:#ecf0f5;">
<div class="article" style="background-color:#ecf0f5;">
<div class="section" style="background-color:#ecf0f5;">
	<h4>契約商品を確認する</h4>
	<table>
		<colgroup>
		<col width="390px">
		<col width="390px">
		</colgroup>
		<tbody>
			<tr>
			<td>
				<h5>
					<router-link class="padtb10 padl15 arrow01top text_large bld" to="/register">契約商品のご登録</router-link>
				</h5>
				<p style="padding-left:20px;">お手持ちの契約商品をこちらからご登録ください。</p>
			</td>
			<td>
				<h5>
					<router-link class="padtb10 padl15 arrow01top text_large bld" to="/check">契約商品のご確認</router-link>
				</h5>
				<p style="padding-left:20px;">お手持ちのすべての契約商品をまとめてご確認できます。</p>
			</td>
			</tr>
		</tbody>
	</table>

	<h4>保険の見直しをする</h4>

	<table>
		<colgroup>
			<col width="390px">
			<col width="390px">
		</colgroup>
		<tbody>
			<tr>
			<td>
				<h5><p class="padtb10 padl15 arrow01top text_large bld"><a href="javascript: void(0);">保険比較シミュレーション</a></p></h5>
				<p style="padding-left:20px;">すべての保険会社の商品をまとめて比較できます。</p>
			</td>
			<td>
				<h5><p class="padtb10 padl15 arrow01top text_large bld"><a href="javascript: void(0);">ポートフォリオ簡単診断</a></p></h5>
				<p style="padding-left:20px;">お手持ちの金融商品をポートフォリオで診断します。</p>
			</td>
			</tr>
			<tr>
			<td>
				<h5><p class="padtb10 padl15 arrow01top text_large bld"><a href="javascript: void(0);">FPウェブ診断（有料会員のみ）</a></p></h5>
				<p style="padding-left:20px;">当連盟のFPとチャットでご相談できます。</p>
			</td>
			</tr>
		</tbody>
	</table>

	<h4>まとめてお手続きする</h4>

	<table>
		<colgroup>
			<col width="390px">
			<col width="390px">
		</colgroup>
		<tbody>
			<tr>
			<td>
				<h5><p class="padtb10 padl15 arrow01top text_large bld"><a href="javascript: void(0);">まとめて資料請求</a></p></h5>
				<p style="padding-left:20px;">すべての保険会社の商品をまとめて資料請求できます。</p>
			</td>
			<td>
				<h5><p class="padtb10 padl15 arrow01top text_large bld"><a href="javascript: void(0);">まとめて保全手続き</a></p></h5>
				<p style="padding-left:20px;">すべての契約商品をまとめてお手続きできます。</p>
			</td>
			</tr>
		</tbody>
	</table>

	<h4>各種変更のお手続き</h4>

	<table>
		<colgroup>
			<col width="390px">
			<col width="390px">
		</colgroup>
		<tbody>
			<tr>
			<td>
				<h5><p class="padtb10 padl15 arrow01top text_large bld"><a href="javascript: void(0);">登録情報の変更</a></p></h5>
				<p style="padding-left:20px;">登録情報の登録、変更ができます。</p>
			</td>
			<td>
				<h5><p class="padtb10 padl15 arrow01top text_large bld"><a href="javascript: void(0);">ご家族情報の登録</a></p></h5>
				<p style="padding-left:20px;">ご家族の情報を登録できます。</p>
			</td>
			</tr>
		</tbody>
	</table>
</div>
</div>
</div>
</div>
</div>
</div>
<div id="cboxOverlay" style="display: none;"></div><div id="colorbox" class="" role="dialog" tabindex="-1" style="display: none;"><div id="cboxWrapper"><div><div id="cboxTopLeft" style="float: left;"></div><div id="cboxTopCenter" style="float: left;"></div><div id="cboxTopRight" style="float: left;">
  </div>
  </div>
  <div style="clear: left;"><div id="cboxMiddleLeft" style="float: left;">
    </div>
    <div id="cboxContent" style="float: left;">
      <div id="cboxTitle" style="float: left;">
        </div>
        <div id="cboxCurrent" style="float: left;">
          </div>
          <button type="button" id="cboxPrevious"></button>
          <button type="button" id="cboxNext"></button>
          <button id="cboxSlideshow"></button>
          <div id="cboxLoadingOverlay" style="float: left;"></div>
          <div id="cboxLoadingGraphic" style="float: left;"></div>
          </div><div id="cboxMiddleRight" style="float: left;"></div>
          </div><div style="clear: left;"><div id="cboxBottomLeft" style="float: left;"></div>
          <div id="cboxBottomCenter" style="float: left;"></div><div id="cboxBottomRight" style="float: left;"></div>
          </div>
          </div>
          <div style="position: absolute; width: 9999px; visibility: hidden; display: none;"></div>
  </div>
</body>
</template>
<script>
export default {
	name: 'TopPage',
}
</script>