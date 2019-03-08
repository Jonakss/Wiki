<!-- TITLE: Activar Windows -->
<!-- SUBTITLE: Metodos para activar windows -->

<span id="breadcrum"></span>
# Activación de windows
### Windows 10
 Microsoft Toolkit <a href="\\freenas\Taller\Activadores"> Freenas (Taller\Activadores) </a>
 
 
 
 
 
 
 <script>
	var fullURL = window.location.pathname;
	var urls = fullURL.split("/");
	var path = "/";
	urls.forEach(function(url){
		document.getElementById("breadcrum").innerHTML += "/";
		if(url == ""){
		document.getElementById("breadcrum").innerHTML += '<a href="/">Home</a>';
		}else{
			path +=url;
			document.getElementById("breadcrum").innerHTML += '<a href="'+ path + '">' + url + '</a>';
		}
	});
</script>
