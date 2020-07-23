<html>
	<head>
		<title>LoginPage</title>
		<meta name='viewport' content='width=device-width, initial-scale=1'>
		<script src='https://kit.fontawesome.com/a076d05399.js'></script>
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
	<style>
		#container{
			background-color: white;
			width: 290px;
  			height: 400px;
  			position: absolute;
  			right: 45%;
  			margin: 3px 0;
			overflow: hidden;
		}
		input[type=email],input[type=password]{
 			 width: 99%;
  			padding: 8px 16px;
  			margin: 1px 0;
  			display: inline-block;
  			border: 1px solid #ccc;
 			border-radius: 4px;
  			box-sizing: border-box;
		}
		input[type=submit],input[type=button]{
			width:100%;
			padding: 10px 18px;
  			margin: 1px 0;
  			display: inline-block;
  			border: 1px solid #ccc;
  			border-radius: 4px;
  			box-sizing: border-box;
  			align:center;
  			color:white;
  			background-color:#5cd6d6;
 
		}
		input[type=button]{
			width:100%;
			padding: 10px 18px;
  			margin: 1px 0;
  			display: inline-block;
  			border: 1px solid #ccc;
  			border-radius: 4px;
  			box-sizing: border-box;
  			align:center;
  			color:white;
  			background-color:lightblue;
 
		}
		.input-icons i {
            			position: absolute;
           
           		}
         
       		.input-icons {
           			width: 100%;
          			margin-bottom: 10px;
           
       		 }
         
		.icon {
           			 padding: 15px;
           			 min-width: 40px;
           			 left:240px;
           			 color:gray;
       		 }
		.icon1 {
            			padding: 15px;
            			min-width: 40px;
            			left:120px;
            			color:white;
        		}
		.icon2 {
            			padding: 3px;
            			min-width: 20px;
            			left:5px;
            			color:white;
		}
		.icon3 {
            			padding: 3px;
          	  		min-width: 20px;
            			right:4px;
            			color:white;
        		}	
		 .input-field {
		            	width: 100%;
            			padding: 30px;
           	 		text-align: left;
        		}

	</style>
	</head>
	<body>
		<div id="container">
			<div align="center" style="background-color:#5cd6d6">
				<div class="input-icons">
					<i class="fa fa-graduation-cap icon2"></i>
					<div  class="input-icons">
						<i class="fa fa-close icon3"></i>
						<h3><font color="white">Sign in</font></h3>
					</div>
				</div>
			</div>
			<form>
			<div class="input-icons">
				<i class="fa fa-envelope icon"></i>
				<input class="input-field" type="email" name="mail" placeholder="Enter your Email" size="30">
			</div>
			<div class="input-icons">
    			<i class="fas fa-unlock icon"></i>
    			<input class="input-field" type="password" name="pwd" placeholder="Enter Password" size="30">
			</div>
			<input type="submit" value="SIGN IN">
			<label style="color:red">Forgot your password?&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspRegister!</label>
			<p></p>
			<p></p>
			<p style="color:black">________________ OR _______________</p>
			<div class="input-icons">
				<i class="fa fa-facebook-f icon1"></i>
				<input  style="background-color:#5c85d6"type="button" size="30">
			</div>
			<p></p>
			<div class="input-icons">
    			<i class="fab fa-Google icon1"></i>
    			<input style="background-color:#ff6666" type="button" size="30">
			</div>
			<p></p>
			<input style="background-color:#ace600" type="submit" value="< EPAM LOGIN >" size="30">
			</form>
		</div>
	</body>
</html>
