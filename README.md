# collision

<html>
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
p {
color: #ffffff;
font-size: 1.5em;
}


.red {color:#ff0000;}
.grey {color:#ffffff; background:#999999;}
.snow {color:#fffafa;}
.yellow {color:#ff0000; background:#ffff00;}
.blue {color:#0000ff;}
.white {color:#ffffff; blinking;}
.waku {border:2px dotted #99cc66;
line-height: 200%;
padding: 10px;}


main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}


/* 点滅 */
.blinking{

-moz-animation:blink 1.5s ease-in-out infinite alternate;
animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@-moz-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/

/*背景を表示させる部分*/
body::before {
content:"";
display:block;
position:fixed;
top:0;
left:0;
z-index:-1;
width:100%;
height:100vh;
background:url(https://torokoid.github.io/20210704_Utsunomiya_swim/20210704_002.JPG) center/cover no-repeat;
-webkit-background-size:cover;/*Android4*/
}

a.p:hover {
position: relative;
text-decoration: none;
}
a.p span {
display: none;
position: relative;
top: -0.5em;
left: 2em;
}
a.p:hover span {
border: none;
display: block;
width: 800px;
}


@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}


</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<body>



<p class="note">
モバイル端末をお使いの場合は、画面を横向きにすると
より見やすくご覧頂けます。
</p>

<!--ここ上は、ほぼそのまま使います！-->


<!--QRコードの挿入例-->
<p align="left"> <img src="collision.png" alt="アクセス用QRコード" width="100">アクセス用QRコード</p>
<p align="right"><marquee direction="left" scrollamount="20" width="30%">(^_^)/~hada</marquee></p>

<!--流れ文字の挿入例-->
<h1><span class="yellow"><marquee behavior="alternate">!!! 2023/03/16 見通しの良い交差点での衝突回避 !!!</marquee></span></h1>	

<!--ここから下が、本体部分-->
<p>田園地帯、見通しの良い交差点ですが、同じ速度で近づいていくと、相手が見えなくなる現象があります。<br>発生場所はJR岡本駅の北東部田園地帯</p>

<a href="20230316_003.png" data-lightbox="abc"><img src="20230316_003.png" alt="サンプル画像" width="900" /></a>
<a href="20230316_004.png" data-lightbox="abc"><img src="20230316_004.png" alt="サンプル画像" width="900" /></a>

<p>GoProで動画が撮れてましたので、YouTubeに挙げました。</p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/WBm2HzGe6rw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<p>相手側の道路は一時停止ですが、路面ペイントは消えかかってます。</p>
<a href="20230316_001.png" data-lightbox="abc"><img src="20230316_001.png" alt="サンプル画像" width="900" /></a>
<p>ちょっと手前の電柱に止まれの標識が付いてました。</p>
<a href="20230316_002.png" data-lightbox="abc"><img src="20230316_002.png" alt="サンプル画像" width="900" /></a>


<p>JAFのHPにこの現象の説明がありました。</p>
<a href="20230316_005.png" data-lightbox="abc"><img src="20230316_005.png" alt="サンプル画像" width="900" /></a>
<a href="https://jaf.or.jp/common/kuruma-qa/category-accident/subcategory-counterplan/faq161">JAF,HPリンク</a>


<!--本体はここまで-->


<!--画面に空白地帯を作って、背景が見えるようにしています-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
<footer>
<p>Copyright 2023/03/16 S.Hada</p>
</footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>



</body>

</html>
