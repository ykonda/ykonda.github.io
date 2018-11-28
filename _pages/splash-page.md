---
title: ""
layout: splash
classes: wide
permalink: /deine-einladung/
date: 2016-03-23T11:48:41-04:00
header:
  image: /assets/images/YuFI.jpg
  actions:
    - label: "Code of Konda"
      url: "https://www.youtube.com/watch?v=XMyeUL8NRXs"
  caption: "Photo credit: [**Tallo**](https://www.youtube.com/watch?v=XMyeUL8NRXs)"
excerpt: "an excerpt"
intro: 
  - excerpt: 'Kartoffel & Kawaii mit Yuria Konda und Finn Linzer. Die
    preisgekrönte, verblüffend fabelhafte, grenzenlos fantastische Party für
    sie, ihn und es.  

    Haltet euch den Abend des 15. Dezember FREI! Weitere Informationen folgen bald.'
---

{% include feature_row id="intro" type="center" %}

<!-- begin wwww.htmlcommentbox.com -->
 <div id="HCB_comment_box"><a href="http://www.htmlcommentbox.com">Widget</a> is loading comments...</div>
 <link rel="stylesheet" type="text/css" href="//www.htmlcommentbox.com/static/skins/bootstrap/twitter-bootstrap.css?v=0" />
 <script type="text/javascript" id="hcb"> /*<!--*/ if(!window.hcb_user){hcb_user={comments_header:'Guestbook'};} (function(){var s=document.createElement("script"), l=hcb_user.PAGE || (""+window.location).replace(/'/g,"%27"), h="//www.htmlcommentbox.com";s.setAttribute("type","text/javascript");s.setAttribute("src", h+"/jread?page="+encodeURIComponent(l).replace("+","%2B")+"&opts=16862&num=10&ts=1543418795416");if (typeof s!="undefined") document.getElementsByTagName("head")[0].appendChild(s);})(); /*-->*/ </script>
<!-- end www.htmlcommentbox.com -->


<html>
<body>

<h1>My First Google Map</h1>

<div id="googleMap" style="width:100%;height:400px;"></div>

<script>
function myMap() {
var mapProp= {
    center:new google.maps.LatLng(51.508742,-0.120850),
    zoom:5,
};
var map=new google.maps.Map(document.getElementById("googleMap"),mapProp);
}
</script>

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDRtIG8VPf8TS_Yl28-OGchRgKDH6v8J3c&callback=myMap"></script>

</body>
</html>
