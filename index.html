<!DOCTYPE html>
<html>
<head>
	<title>password</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">

<style>
body {
    background-image: url("MapWorld.png");
    background-repeat:no-repeat;
    background-size: cover;
    overflow:hidden;
}
#generateDrone{
	margin-top: 20px;
	margin-bottom: 20px;
	margin-left: 30px;


}
.styleButton{
	border-top-right-radius: 10px;
	border-bottom-left-radius: 10px;
	font-size: 15px;
	background-color: #e67e22;
	padding: 8px;
	color: white;

}
#counterOfDrone, #rescue{
	font-size: 19px;
	margin-bottom: 20px;
	margin-left: 30px;
	width: 170px;
	padding: 2px;
	background-color: #e67e22;
	color: white;
	padding-left: 7px;
}
#airPort{
	margin-left: 30px;
	margin-top: 20px;
}
</style>

</head>
<body>



<button class="styleButton" id="generateDrone">Make Drone</button>
<button class="styleButton" id="removeDrone">Remove Drone</button>





<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
<script>


		var counter = 0;
		var RescueCounter = 0;
		
		$("body").append('<div id="counterOfDrone">Counter Of Drone: '+counter+'</div>');
		$("body").append('<div id="rescue">Rescue: '+RescueCounter+'</div>');
		$("body").append('<div id="airPort"></div>');

		function blinker() {
			$(".fa-exclamation-triangle").fadeOut(1000);
	   		$(".fa-exclamation-triangle").fadeIn(1000);
		}

		setInterval(blinker, 2000);

		// button to make your drone and the counter of how many drone that you are making
		$(document).on("click","#generateDrone", function(){

			$("#airPort").append('<div><i class="fa fa-flip-horizontal fa-ambulance" style="font-size:70px; top: 161px; left: 38px; color: #34495e; position: absolute;"></i></div>');
			//$(".fa-ambulance").css("top", "+=80" );
			counter++;
			//console.log("hi"+counter);
			$("#counterOfDrone").text("Counter Of Drone: "+counter);
		});


		// button to remove drone and the counter of drone that has been remove
		$(document).on("click","#removeDrone", function(){

			$(".fa-ambulance").first().remove();

			if (counter <= 0) {
                $("#counterOfDrone").text("Counter Of Drone: 0");
            }else{
				counter--;
				$("#counterOfDrone").text("Counter Of Drone: "+counter);
			}
		});




		var positionX = $(window).width();
		var positionY = $(window).height();

		for(var i = 0; i < 9; i++){
			
			var randomX = Math.floor(Math.random()*positionX);
			var randomY = Math.floor(Math.random()*positionY);
			$("body").append('<div><i class="fa fa-exclamation-triangle" style="font-size:60px; top: '+randomY+'px; left: '+randomX+'px; position: absolute; color: #c0392b"></i></div>');
		

		}

		// give the (this).fa-ambulance a class so you can move it when you click on .fa-exclamation-triangle to see if you have the class
		$(document).on("click",".fa-ambulance", function(){
		
			$(this).addClass("counterDrone");

		});


		// your Rescue point when click on and move the .fa-ambulance if you have the class and remove the same class so it will never move agian.
		$(document).on("click",".fa-exclamation-triangle", function(){

				var p = $(this).position();

					if($(".fa-ambulance").hasClass("counterDrone")) {

							$(".counterDrone").animate({

							top: p.top,
							left: p.left}, 2000);
						
						RescueCounter++;	//add til din "Rescue "+RescueCounter og så print out ikke omvendt !!!
						$("#rescue").text("Rescue: "+RescueCounter);

						$(this).animate({top: 135, left: 180},2000);
						$(this).css({"font-size":"20px"});
						
					}
					
				$(".fa-ambulance").removeClass("counterDrone");
				

		});



</script>



















</body>
</html>

