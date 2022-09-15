<script type="text/javascript" src="js/jquery.min.js"></script>
<script type="text/javascript" src="js/qrcode.js"></script>

# Android apk-k letöltése

## Kedvenc KHZ

<a href="download/com.spc.khzv3.apk" download>SPCKhz v1.0.0.3 (JEGSBO2/KHAZ_PROD)</a>
<div id="qrcodekhz" style="width:100px; height:100px; margin:25px;"></div>

<a href="download/com.spc.khztesztv3.apk" download>SPCKhzTeszt v1.0.0.3 (JEGSBO2/TESZT_KHAZ_UJ)</a>
<div id="qrcodekhzteszt" style="width:100px; height:100px; margin:25px;"></div>

## Kedvenc Sofőr modul

<a href="download/com.spc.soforv3.apk" download>SPCSofor v1.0.0.3 (JEGSBO2/KHAZ_PROD)</a>
<div id="qrcodesofor" style="width:100px; height:100px; margin:25px;"></div>

<a href="download/com.spc.sofortesztv3.apk" download>SPCSoforTeszt v1.0.0.3 (JEGSBO2/TESZT_KHAZ_UJ)</a>
<div id="qrcodesoforteszt" style="width:100px; height:100px; margin:25px;"></div>

<script type="text/javascript">
var qrcodekhz = new QRCode(document.getElementById("qrcodekhz"), {
    text   : "https://humigeri.github.io/download/com.spc.khzv3.apk",
	width  : 100,
	height : 100
});
var qrcodekhzteszt = new QRCode(document.getElementById("qrcodekhzteszt"), {
    text   : "https://humigeri.github.io/download/com.spc.khztesztv3.apk",
	width  : 100,
	height : 100
});
var qrcodesofor = new QRCode(document.getElementById("qrcodesofor"), {
    text   : "https://humigeri.github.io/download/com.spc.soforv3.apk",
	width  : 100,
	height : 100
});
var qrcodesoforteszt = new QRCode(document.getElementById("qrcodesoforteszt"), {
    text   : "https://humigeri.github.io/download/com.spc.sofortesztv3.apk",
	width  : 100,
	height : 100
});

</script>