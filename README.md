finalProject
============

<!DOCTYPE html>
<html>
    
<head>

     
</head>
    
<body>


	<img id = "plane" src="backgroundnew.png"/>	
	<img class="ipod" src="ipodnew.png"/>
	
	<div class="goku" src="goku2.png"></div>
	<div class="hurdle" src="hurdlev2.gif"></div>


	<div class="bye"></div>
	

	
	
</body>


<style>


#plane{
position:relative;
height:400px;
width:550px;
left:80px;
top:180px;
}
.bye{
position:absolute;
left:200px;
top:383px;
z-index:0;
}

.ipod{
height:200px;
width:150px;
left:0px;
top:50px;
position:absolute;
}

.goku{
height:200px;
width:120px;
left:20px;
top:-300px;
position:relative;
}

.hurdle{
height:200px;
width:120px;
left:600px;
top:-300px;
position:relative;
}

.ipad{
transform:          rotate(270deg);
-ms-transform:      rotate(270deg);
-moz-transform:     rotate(270deg);
-webkit-transform:  rotate(270deg);
-o-transform:       rotate(270deg);
}

.goku {
    width: 55px;
    height: 100px;
    background-image: url("goku2.png");
	
    
    -webkit-animation: play .8s steps(10) infinite;
       -moz-animation: play .8s steps(10) infinite;
        -ms-animation: play .8s steps(10) infinite;
         -o-animation: play .8s steps(10) infinite;
            animation: play .8s steps(10) infinite;
}

.hurdle {
    width: 45px;
    height: 100px;
    background-image: url("hurdlev2.gif");
	
    
    -webkit-animation: play .8s steps(12) infinite;
       -moz-animation: play .8s steps(10) infinite;
        -ms-animation: play .8s steps(10) infinite;
         -o-animation: play .8s steps(10) infinite;
            animation: play .8s steps(10) infinite;
}



.bye {
    width: 45px;
    height: 100px;
    background-image: url("sonic2.png");
	
    
    -webkit-animation: play .8s steps(11) infinite;
       -moz-animation: play .8s steps(11) infinite;
        -ms-animation: play .8s steps(11) infinite;
         -o-animation: play .8s steps(11) infinite;
            animation: play .8s steps(10) infinite;
		}


		
		@-webkit-keyframes play {
   from { background-position:   0px; }
     to { background-position: -500px; }
}

@-moz-keyframes play {
   from { background-position:    0px; }
     to { background-position: -500px; }
}

@-ms-keyframes play {
   from { background-position:    0px; }
     to { background-position: -500px; }
}

@-o-keyframes play {
   from { background-position:    0px; }
     to { background-position: -500px; }
}

@keyframes play {
   from { background-position:    0px; }
     to { background-position: -500px; }
}



	
</style>

</html>
