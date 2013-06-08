<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
	<head>
		<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1">
		<title>Feedback</title>
		
		<!--css link-->
		<link rel= "stylesheet" href= "css/indexcss2.css" type="text/css" />
		<br>
	<div id= "navi"> 

		<div id="nav-container" style="max-width: 1000px; margin-left: 0 auto; margin-right: 0 auto;">
			<div id='header'>
				<div id="title">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
				 The Aquarium of Jellyfish
				 <div id="jelly">
				  <img src="jellylogo4.jpg" height="110px" width="390px" > </div> </div>
			</div>
			<div id="bar">
				&nbsp;
				
				<a href= "project1.html"> &nbsp;&nbsp;&nbsp;&nbsp;  Home &nbsp;&nbsp;&nbsp;&nbsp; </a>
				<a href= "hourspage.html"> &nbsp;&nbsp;&nbsp;&nbsp; Visit  &nbsp;&nbsp;&nbsp;&nbsp; </a>
				<a href= "eventpage.html"> &nbsp;&nbsp;&nbsp;&nbsp; Events &nbsp;&nbsp;&nbsp;&nbsp; </a>
				<a href= "gallerypage.html"> &nbsp;&nbsp;&nbsp;&nbsp; Gallery  &nbsp;&nbsp;&nbsp;&nbsp; </a> </a> 	
				<a href= "donationspage.html"> &nbsp;&nbsp;&nbsp;&nbsp; Donations  &nbsp;&nbsp;&nbsp;&nbsp; </a>
				<a href= "http://brittneybarry.com/wordpress/"> &nbsp;&nbsp;&nbsp;&nbsp; Blog  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </a>
				<a href= "mobile.html"> &nbsp;&nbsp;&nbsp;&nbsp; Mobile  &nbsp;&nbsp;&nbsp;&nbsp; </a>
				</p>
			</div>
		</div>
		
	</div>
	
	<br>
		<br>

		<style> background-color:#c8c8c8; </style>
		
		
	</head>
	
	
	<br>
	
	
	<body>
		<p align="center" style="font-color:#000; font-size:28px;"> Thank you! </p> <br>
		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="newsletterpage.html"> Go Back </a>
		<?php
		$mailto="bbbarry_4@yahoo.com";
		$subject="Feedback form";
		$message="Values submitted from web site form";
		$header="From: ".$_POST['CustEmail'];
		foreach ($_POST as $key => $value)
		{
		if (!is_array($value))
		{
		$message .= "\n".$key." : ".$value;
		}
		else
		{
			foreach ($_POST[$key] as $itemvalue)
			{
		$message .= "\n".$key." : " .$itemvalue;
				}
			}
		}
		mail($mailto, $subject, stripslashes($message), $header);
		?>
		<br>
		<br>
		<br>
		
		<div class= "footer" style="color:#181529">   
		 <a href= "http://www.facebook.com/groups/343645662369426/"> <img src="FaceBook-icon.png" alt="facebook" width="20" height="20" </a> 
		 &nbsp; | &nbsp; <a href= "contactpage.html"> Contact </a> &nbsp; | &nbsp; Copyright &copy; 2012
</div>	
		
		
	</body>
</html>
