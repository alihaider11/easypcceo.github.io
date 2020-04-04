---
title: "DPI Calculator / PPI Calculator" 
permalink: "/DpiPpiCalculator/"
layout: page
seotitle: "Dpi | PPi Calculator" 
meta: "If you only have enough room to put your PC on the left side of your desk, choosing a good inverted PC case is your best option."
---
<div class="container-fluid">
<p> For display with square&nbsp;<a href="https://en.wikipedia.org/wiki/Pixel" target="_blank">Pixels.</a></p>
<div class="card">
  <div class="card-header">Monitor Data</div>
  <div class="card-body">
    <div class="row">
        <div class="col-md-3">
            <h4>Horizontal Resolution:</h4>      
            <h4>Vertical Resolution:</h4>      
            <h4>Diagonal:</h4>      
        </div>
        <div class="col-md-6">
            <div class="form-inline">
                <input class="form-control" onChange="do_dpi()" value="1600" type="number" id="txtHR"/>
                <span>&nbsp;pixals,</span> 
                <input class="form-control" onChange="do_dpi()" value="900" type="number" id="txtVR" /><span>&nbsp;pixals,</span>
                <input class="form-control" onChange="do_dpi()" value="20" type="number" id="txtDiagonal"/><span>&nbsp;inches (</span><span id="metricdiag">50.8</span><span>)</span>
            </div>
        </div>
        <div class="col-md-3">
        <h4>Megapixels:</h4><span id="mpix">1.44</span>
        <h4>Aspect Ratio:</h4><span id="aspect">16:9</span>     
        </div>
    </div>    </div>
  <div class="card-footer">
    <p id="result">Display size: 17.43" × 9.81" = 170.92in² (44.28cm × 24.91cm = 1102.71cm²) at <span title="Y: 91.79">91.79</span> <abbr title="pixels per inch">PPI</abbr>, 0.2767mm <a href="https://en.wikipedia.org/wiki/Dot_pitch">dot pitch</a>, 8425 <abbr title="pixels per square inch">PPI²</abbr></p>
    <p id="saved"></p>
    <input type="button" class="btn btn-info" onclick="document.getElementById('saved').innerHTML = document.getElementById('saved').innerHTML + document.getElementById('result').innerHTML + '<br>';" value="Remember">
  </div>
</div>
<p>Noteworthy and common display sizes of monitors, PCs, notebooks, tablets, phablets, smartphones, handhelds and HMDs. Link color takes into account typical viewing distance:</p>
<div id="multilist">
<ul id="mylist" class="row">
<div class="col-md-3">
<li><a href="javascript:set_mon(272,340,1.337)" style="background-color: rgb(247, 255, 191);">272x340 @ 1.337</a> Apple watch 38mm</li><li><a href="javascript:set_mon(312,390,1.534)" style="background-color: rgb(247, 255, 191);">312x390 @ 1.534</a> Apple watch 42mm</li><li><a href="javascript:set_mon(368,448,1.757)" style="background-color: rgb(249, 255, 191);">368x448 @ 1.757</a> Apple watch 44mm</li><li><a href="javascript:set_mon(480,320,3.5)" style="background-color: rgb(191, 255, 198);">480x320 @ 3.5</a> Apple iPhone</li><li><a href="javascript:set_mon(720,720,3.1)" style="background-color: rgb(248, 255, 191);">720x720 @ 3.1</a> Blackberry Q5</li><li><a href="javascript:set_mon(800,240,3.53)" style="background-color: rgb(212, 255, 191);">800x240 @ 3.53</a> Nintendo 3DS (3D)</li><li><a href="javascript:set_mon(800,480,3)" style="background-color: rgb(241, 255, 191);">800x480 @ 3</a> Toshiba Portégé G900</li><li><a href="javascript:set_mon(800,600,6)" style="background-color: rgb(192, 255, 191);">800x600 @ 6</a> Sony Librié</li><li><a href="javascript:set_mon(854,480,3.7)" style="background-color: rgb(223, 255, 191);">854x480 @ 3.7</a> <a href="https://en.wikipedia.org/wiki/Motorola_Droid">Motorola Droid</a></li><li><a href="javascript:set_mon(960,544,5)" style="background-color: rgb(211, 255, 191);">960x544 @ 5</a> Sony PS Vita</li><li><a href="javascript:set_mon(960,640,3.5)" style="background-color: rgb(249, 255, 191);">960x640 @ 3.5</a> Apple iPhone 4/4S</li><li><a href="javascript:set_mon(1024,600,5.6)" style="background-color: rgb(210, 255, 191);">1024x600 @ 5.6</a> Panasonic Toughbook CF-U1</li><li><a href="javascript:set_mon(1024,600,10.1)" style="background-color: rgb(191, 255, 202);">1024x600 @ 10.1</a> Netbooks</li><li><a href="javascript:set_mon(1024,768,6.4)" style="background-color: rgb(208, 255, 191);">1024x768 @ 6.4</a> Sony PCG-U1</li><li><a href="javascript:set_mon(1024,768,7.9)" style="background-color: rgb(196, 255, 191);">1024x768 @ 7.9</a> Apple iPad Mini</li><li><a href="javascript:set_mon(1024,768,8.1)" style="background-color: rgb(195, 255, 191);">1024x768 @ 8.1</a> iRex iLiad</li><li><a href="javascript:set_mon(1024,768,9.7)" style="background-color: rgb(191, 255, 195);">1024x768 @ 9.7</a> Apple iPad (2010)</li><li><a href="javascript:set_mon(1136,640,4)" style="background-color: rgb(247, 255, 191);">1136x640 @ 4</a> Apple iPhone 5/5S/SE</li><li><a href="javascript:set_mon(1280,720,4.3)" style="background-color: rgb(255, 255, 191);">1280x720 @ 4.3</a> Sony Xperia S</li><li><a href="javascript:set_mon(1280,720,6.2)" style="background-color: rgb(223, 255, 191);">1280x720 @ 6.2</a> Nintendo Switch</li><li><a href="javascript:set_mon(1280,800,5.3)" style="background-color: rgb(239, 255, 191);">1280x800 @ 5.3</a> Samsung Galaxy Note</li><li><a href="javascript:set_mon(1280,800,7)" style="background-color: rgb(218, 255, 191);">1280x800 @ 7</a> Oculus Rift DK1</li><li><a href="javascript:set_mon(1280,800,12)" style="background-color: rgb(191, 255, 193);">1280x800 @ 12</a> </li><li><a href="javascript:set_mon(1280,800,13.3)" style="background-color: rgb(191, 255, 196);">1280x800 @ 13.3</a> Sharp Mebius MW70J</li><li><a href="javascript:set_mon(1200,825,9.7)" style="background-color: rgb(196, 255, 191);">1200x825 @ 9.7</a> Kindle DX</li><li><a href="javascript:set_mon(1200,900,7.5)" style="background-color: rgb(213, 255, 191);">1200x900 @ 7.5</a> OLPC XO-1 (b/w mode)</li><li><a href="javascript:set_mon(1280,1024,0.61)" style="background-color: rgb(255, 191, 223);">1280x1024 @ 0.61</a> <a href="http://www.imaging-resource.com/news/2012/01/27/new-evf-makes-it-clear-the-optical-viewfinders-days-are-numbered">MicroOLED microdisplay</a></li><li><a href="javascript:set_mon(1334,750,4.7)" style="background-color: rgb(252, 255, 191);">1334x750 @ 4.7</a> Apple iPhone 6/6S/7/8</li><li><a href="javascript:set_mon(1360,768,11.1)" style="background-color: rgb(196, 255, 191);">1360x768 @ 11.1</a> Asus S6F</li><li><a href="javascript:set_mon(1366,768,11.6)" style="background-color: rgb(194, 255, 191);">1366x768 @ 11.6</a> Apple MacBook Air 11"</li><li><a href="javascript:set_mon(1366,768,15.6)" style="background-color: rgb(191, 255, 199);">1366x768 @ 15.6</a> </li><li><a href="javascript:set_mon(1400,1050,12)" style="background-color: rgb(201, 255, 191);">1400x1050 @ 12</a> Toshiba Portege M200</li><li><a href="javascript:set_mon(1440,900,13.3)" style="background-color: rgb(194, 255, 191);">1440x900 @ 13.3</a> Lenovo Thinkpad X300</li><li><a href="javascript:set_mon(1440,900,19)" style="background-color: rgb(191, 255, 200);">1440x900 @ 19</a> </li><li><a href="javascript:set_mon(1440,960,15.2)" style="background-color: rgb(191, 255, 192);">1440x960 @ 15.2</a> Apple PowerBook G4</li><li><a href="javascript:set_mon(1440,1440,4.5)" style="background-color: rgb(255, 209, 191);">1440x1440 @ 4.5</a> BlackBerry Passport</li><li><a href="javascript:set_mon(1600,768,8)" style="background-color: rgb(225, 255, 191);">1600x768 @ 8</a> Sony Vaio P-Series</li><li><a href="javascript:set_mon(1600,900,13.1)" style="background-color: rgb(201, 255, 191);">1600x900 @ 13.1</a> Sony Vaio VGN-Z11WN/B</li><li><a href="javascript:set_mon(1600,900,17.3)" style="background-color: rgb(191, 255, 192);">1600x900 @ 17.3</a> </li><li><a href="javascript:set_mon(1620,1080,4.5)" style="background-color: rgb(255, 217, 191);">1620x1080 @ 4.5</a> BlackBerry KEYone</li>
</div>
<div class="col-md-3">
<li><a href="javascript:set_mon(1680,945,18.4)" style="background-color: rgb(192, 255, 191);">1680x945 @ 18.4</a> Sony Vaio VGN-AW11M/H</li><li><a href="javascript:set_mon(1680,1050,15.4)" style="background-color: rgb(201, 255, 191);">1680x1050 @ 15.4</a> Sony Vaio FS92</li><li><a href="javascript:set_mon(1792,768,14.4)" style="background-color: rgb(202, 255, 191);">1792x768 @ 14.4</a> Toshiba Satellite U840W</li><li><a href="javascript:set_mon(1792,828,6.1)" style="background-color: rgb(255, 250, 191);">1792x828 @ 6.1</a> Apple iPhone XR</li><li><a href="javascript:set_mon(1872,1404,10.3)" style="background-color: rgb(238, 255, 191);">1872x1404 @ 10.3</a> reMarkable</li><li><a href="javascript:set_mon(1920,1080,0.74)" style="background-color: rgb(255, 191, 223);">1920x1080 @ 0.74</a> <a href="http://www.siliconmicrodisplay.com/st1080.html">Silicon Micro Display ST1080</a></li><li><a href="javascript:set_mon(1920,1080,4.7)" style="background-color: rgb(255, 201, 191);">1920x1080 @ 4.7</a> HTC One</li><li><a href="javascript:set_mon(1920,1080,5.5)" style="background-color: rgb(255, 222, 191);">1920x1080 @ 5.5</a> Apple iPhone 6 Plus</li><li><a href="javascript:set_mon(1920,1080,5.7)" style="background-color: rgb(255, 226, 191);">1920x1080 @ 5.7</a> Playstation VR</li><li><a href="javascript:set_mon(1920,1080,11.6)" style="background-color: rgb(224, 255, 191);">1920x1080 @ 11.6</a> Asus Zenbook UX21A</li><li><a href="javascript:set_mon(1920,1152,10.1)" style="background-color: rgb(234, 255, 191);">1920x1152 @ 10.1</a> Lenovo IdeaTab K2</li><li><a href="javascript:set_mon(1920,1200,7)" style="background-color: rgb(255, 244, 191);">1920x1200 @ 7</a> Google Nexus 7 (2013)</li><li><a href="javascript:set_mon(1920,1200,10.1)" style="background-color: rgb(236, 255, 191);">1920x1200 @ 10.1</a> Acer Iconia Tab A700</li><li><a href="javascript:set_mon(1920,1200,15.4)" style="background-color: rgb(212, 255, 191);">1920x1200 @ 15.4</a> IBM Thinkpad T61p</li><li><a href="javascript:set_mon(1920,1200,24)" style="background-color: rgb(196, 255, 191);">1920x1200 @ 24</a> </li><li><a href="javascript:set_mon(1920,1920,26.5)" style="background-color: rgb(207, 255, 191);">1920x1920 @ 26.5</a> Eizo EV2730Q</li><li><a href="javascript:set_mon(2040,1080,6.4)" style="background-color: rgb(255, 232, 191);">2040x1080 @ 6.4</a> Xiaomi Mi MIX</li><li><a href="javascript:set_mon(2048,1152,23)" style="background-color: rgb(200, 255, 191);">2048x1152 @ 23</a> Samsung 2343BW</li><li><a href="javascript:set_mon(2048,1536,0.83)" style="background-color: rgb(255, 191, 223);">2048x1536 @ 0.83</a> Forth Dimension QXGA-R9</li><li><a href="javascript:set_mon(2048,1536,7.9)" style="background-color: rgb(255, 238, 191);">2048x1536 @ 7.9</a> iPad mini w/ Retina display</li><li><a href="javascript:set_mon(2048,1536,9.7)" style="background-color: rgb(254, 255, 191);">2048x1536 @ 9.7</a> iPad (3rd gen.)</li><li><a href="javascript:set_mon(2048,1536,15)" style="background-color: rgb(225, 255, 191);">2048x1536 @ 15</a> NEC Versa Pro NX VA20S/AE</li><li><a href="javascript:set_mon(2048,1536,20.8)" style="background-color: rgb(211, 255, 191);">2048x1536 @ 20.8</a> Iiyama ProLite H530-B</li><li><a href="javascript:set_mon(2048,2048,1)" style="background-color: rgb(255, 191, 223);">2048x2048 @ 1</a> <a href="http://www.kopin.com/investors/news-events/press-releases/press-release-details/2017/Kopin-Debuts-Lightning-OLED-Microdisplay-With-2k-x-2k-Resolution-for-Mobile-VR-at-2017-CES/default.aspx">Kopin Lightning</a></li><li><a href="javascript:set_mon(2160,1080,5.5)" style="background-color: rgb(255, 205, 191);">2160x1080 @ 5.5</a> LG Q6</li><li><a href="javascript:set_mon(2200,1650,13.3)" style="background-color: rgb(240, 255, 191);">2200x1650 @ 13.3</a> Sony DPT-RP1</li><li><a href="javascript:set_mon(2224,1080,5.84)" style="background-color: rgb(255, 209, 191);">2224x1080 @ 5.84</a> Huawei P20</li><li><a href="javascript:set_mon(2224,1668,10.5)" style="background-color: rgb(255, 251, 191);">2224x1668 @ 10.5</a> Apple iPad Pro 10.5"</li><li><a href="javascript:set_mon(2304,1440,12)" style="background-color: rgb(246, 255, 191);">2304x1440 @ 12</a> Apple MacBook</li><li><a href="javascript:set_mon(2400,1600,12.3)" style="background-color: rgb(251, 255, 191);">2400x1600 @ 12.3</a> Google Pixelbook</li><li><a href="javascript:set_mon(2436,1125,5.8)" style="background-color: rgb(255, 193, 191);">2436x1125 @ 5.8</a> Apple iPhone X</li><li><a href="javascript:set_mon(2560,1080,25)" style="background-color: rgb(211, 255, 191);">2560x1080 @ 25</a> LG 25UM65-P</li><li><a href="javascript:set_mon(2560,1312,5.71)" style="background-color: rgb(255, 191, 206);">2560x1312 @ 5.71</a> Essential PH-1</li><li><a href="javascript:set_mon(2560,1440,5.1)" style="background-color: rgb(255, 191, 223);">2560x1440 @ 5.1</a> Samsung Galaxy S6/S7</li><li><a href="javascript:set_mon(2560,1440,11.6)" style="background-color: rgb(255, 252, 191);">2560x1440 @ 11.6</a> Dell XPS 11</li><li><a href="javascript:set_mon(2560,1440,27)" style="background-color: rgb(214, 255, 191);">2560x1440 @ 27</a> Apple iMac 27</li><li><a href="javascript:set_mon(2560,1536,5.5)" style="background-color: rgb(255, 191, 221);">2560x1536 @ 5.5</a> Meizu MX4G</li><li><a href="javascript:set_mon(2560,1600,5.6)" style="background-color: rgb(255, 191, 220);">2560x1600 @ 5.6</a> Samsung Galaxy Note Edge</li><li><a href="javascript:set_mon(2560,1600,8.9)" style="background-color: rgb(255, 224, 191);">2560x1600 @ 8.9</a> Kindle Fire HDX 8.9</li><li><a href="javascript:set_mon(2560,1600,10.055)" style="background-color: rgb(255, 236, 191);">2560x1600 @ 10.055</a> Google Nexus 10</li>
</div>
<div class="col-md-3">
<li><a href="javascript:set_mon(2560,1600,13.3)" style="background-color: rgb(252, 255, 191);">2560x1600 @ 13.3</a> Apple Retina MacBook Pro 13"</li><li><a href="javascript:set_mon(2560,1700,12.85)" style="background-color: rgb(255, 253, 191);">2560x1700 @ 12.85</a> Chromebook Pixel</li><li><a href="javascript:set_mon(2560,1600,30)" style="background-color: rgb(213, 255, 191);">2560x1600 @ 30</a> </li><li><a href="javascript:set_mon(2560,1800,10.2)" style="background-color: rgb(255, 231, 191);">2560x1800 @ 10.2</a> Google Pixel C</li><li><a href="javascript:set_mon(2560,2048,20.1)" style="background-color: rgb(238, 255, 191);">2560x2048 @ 20.1</a> <a href="http://www.necdisplay.com/p/medical%20-diagnostic%20-displays/md205mg-1?type=support">NEC MD205MG-1</a></li><li><a href="javascript:set_mon(2688,1242,6.5)" style="background-color: rgb(255, 191, 193);">2688x1242 @ 6.5</a> Apple iPhone XS Max</li><li><a href="javascript:set_mon(2732,2048,12.9)" style="background-color: rgb(255, 238, 191);">2732x2048 @ 12.9</a> Apple iPad Pro 12.9"</li><li><a href="javascript:set_mon(2736,1824,12.3)" style="background-color: rgb(255, 240, 191);">2736x1824 @ 12.3</a> Microsoft Surface Pro 4</li><li><a href="javascript:set_mon(2880,1440,5.7)" style="background-color: rgb(255, 191, 223);">2880x1440 @ 5.7</a> LG G6</li><li><a href="javascript:set_mon(2880,1620,15.6)" style="background-color: rgb(253, 255, 191);">2880x1620 @ 15.6</a> ASUS UX51VZ</li><li><a href="javascript:set_mon(2880,1800,15.4)" style="background-color: rgb(255, 252, 191);">2880x1800 @ 15.4</a> Apple Retina MacBook Pro 15"</li><li><a href="javascript:set_mon(2960,1440,5.8)" style="background-color: rgb(255, 191, 223);">2960x1440 @ 5.8</a> Samsung Galaxy S8</li><li><a href="javascript:set_mon(2960,1440,6.2)" style="background-color: rgb(255, 191, 223);">2960x1440 @ 6.2</a> Samsung Galaxy S8+</li><li><a href="javascript:set_mon(3000,2000,13.5)" style="background-color: rgb(255, 234, 191);">3000x2000 @ 13.5</a> Microsoft Surface Book</li><li><a href="javascript:set_mon(3040,1440,6.1)" style="background-color: rgb(255, 191, 223);">3040x1440 @ 6.1</a> Samsung Galaxy S10</li><li><a href="javascript:set_mon(3040,1440,6.4)" style="background-color: rgb(255, 191, 223);">3040x1440 @ 6.4</a> Samsung Galaxy S10+</li><li><a href="javascript:set_mon(3072,1920,16)" style="background-color: rgb(255, 246, 191);">3072x1920 @ 16</a> Macbook Pro 16"</li><li><a href="javascript:set_mon(3120,1440,6.1)" style="background-color: rgb(255, 191, 223);">3120x1440 @ 6.1</a> LG G7</li><li><a href="javascript:set_mon(3200,1800,13.3)" style="background-color: rgb(255, 230, 191);">3200x1800 @ 13.3</a> Samsung Ativ Q</li><li><a href="javascript:set_mon(3240,2160,15)" style="background-color: rgb(255, 230, 191);">3240x2160 @ 15</a> Microsoft Surface Book 2 15"</li><li><a href="javascript:set_mon(3280,2048,30)" style="background-color: rgb(239, 255, 191);">3280x2048 @ 30</a> NEC MD MD302C6</li><li><a href="javascript:set_mon(3440,1440,29)" style="background-color: rgb(236, 255, 191);">3440x1440 @ 29</a> LG UM95</li><li><a href="javascript:set_mon(3840,1600,37.5)" style="background-color: rgb(240, 255, 191);">3840x1600 @ 37.5</a> Acer XR382CQK</li><li><a href="javascript:set_mon(3840,2160,5.5)" style="background-color: rgb(255, 191, 223);">3840x2160 @ 5.5</a> Sony Z5 Premium</li><li><a href="javascript:set_mon(3840,2160,15.6)" style="background-color: rgb(255, 213, 191);">3840x2160 @ 15.6</a> </li><li><a href="javascript:set_mon(3840,2160,23.6)" style="background-color: rgb(255, 242, 191);">3840x2160 @ 23.6</a> Acer K242HQKbmjdp</li><li><a href="javascript:set_mon(3840,2160,28)" style="background-color: rgb(255, 251, 191);">3840x2160 @ 28</a> Lenovo ThinkVision 28</li><li><a href="javascript:set_mon(3840,2160,31.5)" style="background-color: rgb(254, 255, 191);">3840x2160 @ 31.5</a> Asus PQ321</li><li><a href="javascript:set_mon(3840,2400,22.2)" style="background-color: rgb(255, 234, 191);">3840x2400 @ 22.2</a> <a href="https://en.wikipedia.org/wiki/IBM_T220/T221_LCD_monitors#IBM_T221">IBM T221</a></li><li><a href="javascript:set_mon(3840,2560,20)" style="background-color: rgb(255, 224, 191);">3840x2560 @ 20</a> Panasonic Toughpad 4K UT-MB4</li><li><a href="javascript:set_mon(4096,2160,31)" style="background-color: rgb(255, 249, 191);">4096x2160 @ 31</a> LG 31MU95</li><li><a href="javascript:set_mon(4096,2160,36.4)" style="background-color: rgb(254, 255, 191);">4096x2160 @ 36.4</a> <a href="http://www.eizo.com/na/products/duravision/fdh3601/">Eizo FDH3601</a></li><li><a href="javascript:set_mon(4096,2304,21.5)" style="background-color: rgb(255, 226, 191);">4096x2304 @ 21.5</a> Retina iMac 21.5"</li><li><a href="javascript:set_mon(5120,1440,49)" style="background-color: rgb(255, 247, 191);">5120x1440 @ 49</a> LG 49WL95C-W</li><li><a href="javascript:set_mon(5120,2160,34)" style="background-color: rgb(255, 226, 191);">5120x2160 @ 34</a> LG 34WK95U</li><li><a href="javascript:set_mon(5120,2880,27)" style="background-color: rgb(255, 203, 191);">5120x2880 @ 27</a> Dell UP2715K, Retina iMac 27"</li><li><a href="javascript:set_mon(6016,3384,32)" style="background-color: rgb(255, 191, 200);">6016x3384 @ 32</a> Apple Pro Display XDR</li><li><a href="javascript:set_mon(7680,4320,17.3)" style="background-color: rgb(255, 191, 223);">7680x4320 @ 17.3</a> JDI LCD prototype</li><li><a href="javascript:set_mon(7680,4320,31.5)" style="background-color: rgb(255, 191, 223);">7680x4320 @ 31.5</a> Dell UP3218K</li><li><a href="javascript:set_mon(7680,4320,70)" style="background-color: rgb(255, 191, 212);">7680x4320 @ 70</a> Sharp Aquos 8K LC-70X500</li>
</div>
<div class="col-md-3">
<li><a href="javascript:set_mon(10240,4320,82)" style="background-color: rgb(255, 191, 223);">10240x4320 @ 82</a> Boe LCD prototype</li>


<li style="list-style-type: none;" id="resolutions"> <b>Resolutions</b>
</li><li><a href="javascript:set_mon(320,240)">320x240</a> QVGA</li>
<li><a href="javascript:set_mon(640,480)">640x480</a> VGA (NTSC square)</li>
<li><a href="javascript:set_mon(768,576)">768x576</a> PAL (square)</li>
<li><a href="javascript:set_mon(800,600)">800x600</a> SVGA</li>
<li><a href="javascript:set_mon(960,540)">960x540</a> qHD</li>
<li><a href="javascript:set_mon(1024,768)">1024x768</a> XGA</li>
<li><a href="javascript:set_mon(1280,720)">1280x720</a> HDTV, 720p</li>
<li><a href="javascript:set_mon(1280,1024)">1280x1024</a> SXGA</li>
<li><a href="javascript:set_mon(1366,768)">1366x768</a> HD</li>
<li><a href="javascript:set_mon(1400,1050)">1400x1050</a> SXGA+</li>
<li><a href="javascript:set_mon(1440,900)">1440x900</a> WSXGA</li>
<li><a href="javascript:set_mon(1600,900)">1600x900</a> HD+, 900p</li>
<li><a href="javascript:set_mon(1600,1200)">1600x1200</a> UXGA</li>
<li><a href="javascript:set_mon(1680,945)">1680x945</a> WXGA++</li>
<li><a href="javascript:set_mon(1680,1050)">1680x1050</a> WSXGA+</li>
<li><a href="javascript:set_mon(1920,1080)">1920x1080</a> HDTV 1080, FullHD, 1080p</li>
<li><a href="javascript:set_mon(1920,1200)">1920x1200</a> WUXGA</li>
<li><a href="javascript:set_mon(2048,1536)">2048x1536</a> QXGA</li>
<li><a href="javascript:set_mon(2560,1080)">2560x1080</a> UW-UXGA</li>
<li><a href="javascript:set_mon(2560,1440)">2560x1440</a> WQHD, 1440p</li>
<li><a href="javascript:set_mon(2560,1600)">2560x1600</a> WQXGA</li>
<li><a href="javascript:set_mon(3200,1600)">3200x1600</a> QHD+</li>
<li><a href="javascript:set_mon(3440,1440)">3440x1440</a> UW-QHD</li>
<li><a href="javascript:set_mon(3840,1600)">3840x1600</a> UW-QHD+</li>
<li><a href="javascript:set_mon(3840,2160)">3840x2160</a> <a href="https://en.wikipedia.org/wiki/4K_resolution#QFHD_.283840x2160.29">QFHD</a>, 4K, UltraHD, UHD-1</li>
<li><a href="javascript:set_mon(3840,2400)">3840x2400</a> WQUXGA</li>
<li><a href="javascript:set_mon(4096,2160)">4096x2160</a> DCI 4K</li>
<li><a href="javascript:set_mon(5120,2880)">5120x2880</a> 5K</li>
<li><a href="javascript:set_mon(7680,4320)">7680x4320</a> <a href="https://en.wikipedia.org/wiki/8K_resolution">8K UHD</a>, UHD-2</li>
<li><a href="javascript:set_mon(7680,4800)">7680x4800</a> WHUXGA</li>
<b>Display sizes</b><br>
<a href="javascript:set_mon(0,0,7)">7"</a>
<a href="javascript:set_mon(0,0,9.7)">9.7"</a>
<a href="javascript:set_mon(0,0,10.1)">10.1"</a>
<a href="javascript:set_mon(0,0,11.6)">11.6"</a>
<a href="javascript:set_mon(0,0,12.1)">12.1"</a>
<a href="javascript:set_mon(0,0,13.3)">13.3"</a><br>
<a href="javascript:set_mon(0,0,14)">14"</a>
<a href="javascript:set_mon(0,0,15.6)">15.6"</a>
<a href="javascript:set_mon(0,0,17)">17"</a> 
<a href="javascript:set_mon(0,0,18.5)">18.5"</a><br>
<a href="javascript:set_mon(0,0,19)">19"</a>
<a href="javascript:set_mon(0,0,20)">20"</a>
<a href="javascript:set_mon(0,0,21.5)">21.5"</a> 
<a href="javascript:set_mon(0,0,22)">22"</a>
<a href="javascript:set_mon(0,0,23)">23"</a>
<a href="javascript:set_mon(0,0,23.6)">23.6"</a><br>
<a href="javascript:set_mon(0,0,24)">24"</a>
<a href="javascript:set_mon(0,0,27)">27"</a>
<a href="javascript:set_mon(0,0,30)">30"</a>
<a href="javascript:set_mon(0,0,32)">32"</a>
<a href="javascript:set_mon(0,0,37)">37"</a> 
<a href="javascript:set_mon(0,0,42)">42"</a>
<a href="javascript:set_mon(0,0,46)">46"</a><br>
<a href="javascript:set_mon(0,0,50)">50"</a>
<a href="javascript:set_mon(0,0,60)">60"</a>
<a href="javascript:set_mon(0,0,65)">65"</a>
</div>
</ul>
</div>

</div>
<script type="text/javascript">
function round2 (i) {
    return Math.round(i * 100) / 100;
}
function do_dpi () {
	if (! document.getElementById ) {
		alert("Your browser does not support the basic DOM API, sorry.");
		return;
	}
   var x = document.getElementById('txtHR').value;
   var y = document.getElementById('txtVR').value;
   var diag = document.getElementById('txtDiagonal').value;
	if (y == 0 || x == 0) return;
	var result = calc_dpi(x,y,diag);
	document.getElementById('metricdiag').innerHTML = round2(result.metricdiag);
	document.getElementById('result').innerHTML =
		'Display size: ' + round2(result.sizex) + '" &times; ' + round2(result.sizey) + '" = ' + 
		round2(result.area) + 'in&sup2; (' +
		round2(result.metricsizex) + 'cm &times; ' + round2(result.metricsizey) + 'cm = ' +
		round2(result.metricarea) + 'cm&sup2;) at ' + 
		'<span title="Y: ' + round2(result.yppi) + '">' + round2(result.xppi) + '</span>' +
		' <abbr title="pixels per inch">PPI</abbr>, ' +
		Math.round(result.dotpitch * 10000)/10000 +
		'mm <a href="https://en.wikipedia.org/wiki/Dot_pitch">dot pitch</a>, ' +
		Math.round(result.sqppi) +
		' <abbr title="pixels per square inch">PPI&sup2;</abbr>';
	document.getElementById('aspect').innerHTML = aspect_ratio(x,y);
	document.getElementById('mpix').innerHTML = in_megapixels(x,y);
}
function calc_dpi (x,y,diag) {
	var ratio = y/x;
	var xd = Math.sqrt( Math.pow(diag,2) / ( 1 + Math.pow(ratio, 2) ));
	var yd = xd * ratio;
	var pitch = 25.4/(x/xd); // metric
	var result = {
		metricdiag : diag * 2.54,
		sizex : xd,
		sizey : yd,
		area  : xd*yd,
		metricsizex : 2.54*xd,
		metricsizey : 2.54*yd,
		metricarea : xd*yd * 2.54*2.54,
		xppi : x/xd,
		yppi : y/yd,
		dotpitch : pitch,
		sqppi : x/xd*y/yd
    };
    return result;
}
function in_megapixels (x,y) {
	return round2(x*y/1000000);
}
function aspect_ratio (x,y) {
	var car = { // common aspect ratios we recognize
		"3:4" : 3/4,
		"1:1" : 1,
		"5:4" : 5/4,
		"4:3" : 4/3,
		"IMAX 1.43:1" : 1.43,
		"3:2" : 3/2,
		"5:3" : 5/3,
		"14:9" : 14/9,
		"16:10" : 16/10,
		"16:9" : 16/9,
		"17:9" : 17/9,
		"21:9" : 21/9,
//		"Academy ratio 1.375:1" : 1.375,
//		"CinemaScope 2.35:1" : 2.35,
//		"Cinemara 2.59:1" : 2.59,
//		"Ultra Panavision 70 2.75:1" : 2.75,
//		"MGM 65 2.76:1" : 2.76,
	};
	var ratio = x/y;
	for (ratio_name in car) {
		var r2 = car[ratio_name];
		if (Math.abs(r2/ratio-1) < 0.016)  // 1.6% error margin is ok
			return ratio_name;
	}
	// this aspect ratio is unknown.
	if (x-0 > y-0) // "1.xx:1"
		return round2(x/y) + ":1";
	else
		return "1:" + round2(y/x);
}
function set_mon (x, y, diag) {
	if (x)
		document.getElementById('txtHR').value = x;
	if (y)
		document.getElementById('txtVR').value = y;
	if (diag) 
		document.getElementById('txtDiagonal').value = diag;
	do_dpi();
}
</script>

