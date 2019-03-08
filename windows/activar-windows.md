<!-- TITLE: Activar Windows -->
<!-- SUBTITLE: Metodos para activar windows -->

<script>
$(document).ready(function(){
var a = document.getElementById("title");
var span = document.createElement("span");
span.setAttribute("id", "breadcrum");
var fc = a.parentElement.ChildNodes[2];
a.parentElement.insertBefore(span, fc);

var fullURL = window.location.pathname;var urls = fullURL.split("/");var path = "/";urls.forEach(function(url){if(url == ""){document.getElementById("breadcrum").innerHTML += '<a href="/">Home</a>';}else{document.getElementById("breadcrum").innerHTML += " > ";path +=url + "/";document.getElementById("breadcrum").innerHTML += '<a href="'+ path + '">' + url + '</a>';}});});</script>
# Activación de windows
### Windows 10
 Microsoft Toolkit <a href="\\freenas\Taller\Activadores"> Freenas (Taller\Activadores) </a>
 
 

