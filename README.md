<!doctype html>
<html> 
<head>
<meta charset="utf-8"> 
<meta name = "viewport" content="width=device-width,initial-scale=1">
<title >Task 1</title>


  <style>
* {
	box-sizing: border-box; 
}
	
	h1 {
		margin-bottom: 100px;
	}

	p{
		border: 2px solid black; 
		background-color: #808080;
		padding: 20px 40px 20px 40px; 
		width: 90%;
		height: 190px;
		margin-right: auto;
		margin-left: auto;
		font-family: Helvetica; 
		color: white;

	
	}

	bloque {
    width: 120px;
    height: 35px;
    line-height: 50px;
    font-size: inherit; /* Indiferente */
    float: right; /* Y (relacionado con align-items) */
    text-align: center;
    color: white;
    border: 2px solid black; 
    margin-top: -20px; 
    margin-right: -42px;

}

	
	#content{
		background-color: #d0166a;
	}

	.row {
		width: 100%;
	}
	@media (min-width: 1200px){
		.col-lg-1,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,
		.col-lg-8,.col-lg-9,.col-lg-10,.col-lg-11,.col-lg-12 {
			float: left;
			border: 1px ; 
			 position: relative;
			 left: 160px;
			

		}
		.col-lg-1{
			width: 8.33%;
		}
		.col-lg-2{
			width: 16.66%;
		}
		.col-lg-3{
			width: 25%;

		}
		.col-lg-4{
			width: 33%;
		}
		.col-lg-5{
			width: 41.66%;
		}
		.col-lg-6{
			width: 50%;
		}
		.col-lg-7{
			width: 58.33%;
		}
		.col-lg-8{
			width: 66.66%;
		}
		.col-lg-9{
			width: 74.99%;
		}
		.col-lg-10{
			width: 83.33%;
		}
		.col-lg-11 {
			width: 91.66%;
		}
		.col-lg-12{
			width: 100%;
		}
	}

	@media(min-width: 950px) and (max-width: 1199px){
		.col-md-1,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,
		.col-md-8,.col-md-9,.col-md-10,.col-md-11,.col-md-12{
			float:left;
		   border: 1px ; 
		   position: relative;
		   left: 160px;
		}
		.col-md-1 {
			width: 8.33%;
		} 
		.col-md-2 {
			width: 16.66%;
		}
		.col-md-3 {
			width: 25%;

		}
		.col-md-4 {
			width: 33%;
		} 
		.col-md-5 {
			width: 41.66%;
		} 
		.col-md-6 {
			width: 50%;
		} 
		.col-md-7 {
			width: 58.33%;
		} 
		.col-md-8 {
			width: 66.66%;
		} 
		.col-md-9 {
			width: 74.99%;
		} 
		.col-md-10 {
			width: 83.33%;
		} 
		.col-md-11 {
			width: 91.66%;
		} 
		.col-md-12 {
			width: 100%;
		} 
	}
</style>
</head>

<body> 
	<h1 align="center"> Our Menu  </h1>
	
    <div class="row"> 
		    <div class="col-lg-3 col-md-6"><p><bloque style="background-color:#F1948A"><font color="black"><b>Chicken</b></font></bloque><br>Lorem ipsum dolor sit amet,consectetur adipisicing elit, sed do eiusmod tempor incididunt
		    ut labore et dolore magna aliqua. ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisiut aliquid ex ea commodo consequat.</p> 
                 
		    </div>
			<div class="col-lg-3 col-md-6"><p><bloque style="background-color:#C0392B"><b>Beef</b></bloque><br>Lorem ipsum dolor sit amet,consectetur adipisicing elit, sed do eiusmod tempor incididunt
		    ut labore et dolore magna aliqua. ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisiut aliquid ex ea commodo consequat. </p>
		     </div>


			<div class="col-lg-3 col-md-6"><p><bloque style="background-color: #F9E79F"><font color="black" weight="bold"><b>Sushi</b></font></bloque><br>Lorem ipsum dolor sit amet,consectetur adipisicing elit, sed do eiusmod tempor incididunt
		    ut labore et dolore magna aliqua. ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisiut aliquid ex ea commodo consequat.</p> 

		</div>
    </div>

	
</body>


</html>

