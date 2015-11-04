<!DOCTYPE HTML>

<html lang="en-US">

<head>

	<meta charset="UTF-8">

	<title>rain</title>

	<script type="text/javascript" src="rainyday.min.js"></script>

	<style type="text/css">

		*{margin:0;padding:0;}

		body{height:100%;}

		.alan{width:100%;height:100%;float:left;}

	</style>

</head>

<body>


<img src="http://www.flash-screen.com/free-wallpaper/beautiful-girl-and-umbrella-facebook-timeline-cover/red-lip-girl-and-umbrella-facebook-timeline-cover,1024x600,67097.jpg" class="alan" id="alan-1" />



	<script type="text/javascript">

		function yagmur() {

				var resim = document.getElementById("alan-1");

				resim.onload = function() {

					var efekt = new RainyDay({

						image:this,

						blur:-7

					});

					efekt.rain([ [1,3, 5] ],12);

				};

				resim.crossOrigin="anonymous";

				resim.src="http://www.flash-screen.com/free-wallpaper/beautiful-girl-and-umbrella-facebook-timeline-cover/red-lip-girl-and-umbrella-facebook-timeline-cover,1024x600,67097.jpg";

			}



		yagmur();

	</script>
	<audio controls autoplay>

  <source src="music/6c4730302ad7e2.mp3" type="audio/mpeg">	<source src="http://www.boxca.com/lctj4xdqkhjr/Evgeny_Grinko_-_Вальс_.mp3" type="audio/mpeg">	<source src="http://pressplayaudio.com/?artist=Evgeny-Grinko&track=Field.ogg" type="audio/ogg">

	Your browser does not support the audio element.
	</audio>


</body>

</html>
