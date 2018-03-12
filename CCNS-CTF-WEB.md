# CCNS CTF WEB WRITE-UP

## Log is important

看瀏覽器中的輸出資料得知flag
<br>
CCNS{53lf_x55}
<br>
## Frontend engineer

F12原始碼中 題目註解藏flag

`<span class="chal-desc"><h4>誠徵前端工程師</h4>`<br>
`<p><strong>需求：</strong></p>`<br>
`<ol><li>熟悉 html, css</li><li>無經驗可</li><li>有寫註解的習慣</li></ol>`<br>
<br>
`<p><strong>待遇：</strong></p>`<br>
`<ul><li>５０點</li></ul>`<br>
<br>
`<!-- CCNS{fr0n73nd_5uck5} --></span>`<br>
<br>
## 妹妹的臉書帳號

一個登入系統 題目給了username了 直接試著Sqlinjection<br>
username: imouto  <br>
password: 'or'1'='1<br>
得到flag<br>
CCNS{YO_HAVE_NO_SISTER}<br>
<br>
## ㄌㄌㄎ

從原始碼中得到一串script<br>
`<script src="source.js"></script>`<br>
直接帶入網址<br>
得到flag<br>
CCNS{1o1i_5aik0u_87euihkjr484uirhgur48terheirqo34895tur48<br>
4uirhgur48terhioo43895tyuhieiwo493r89t4uihjefwio4r8uguihere<br>
rheirqo34pw4uihp49tiueghrulw485tygehur484tugiq34quoireugt<br>
82q3pwreuw485tygehur484tugiq34quoireugt82eghpt87tq38ihw<br>
ergi3uhto8fui3ythow83hp49tiueghrulw485tygehur484tugiq34qu<br>
oireugt82q3pwreui4rhofw8ueirhfow873uiergtw8o48t7yololilolilo<br>
li}<br>
沒錯 就是那麼長
