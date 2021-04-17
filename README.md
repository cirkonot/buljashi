<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" name="viewport" content="width=device-width, initial-scale=1"/>
		<link rel="stylesheet" type="text/css" href="css/bootstrap.css"/>
	</head>
<body>
	<nav class="navbar navbar-default">
		<div class="container-fluid">
			<a class="navbar-brand" href="https://sourcecodester.com">Sourcecodester</a>
		</div>
	</nav>
	<div class="col-md-3"></div>
	<div class="col-md-6 well">
		<h3 class="text-primary">JavaScript - Simple Alarm Clock</h3>
		<hr style="border-top:1px dotted #ccc;"/>
		<center>
			<input type="datetime-local" id="alarmTime"/>
			<button type="button" onclick="setAlarm(this);" id="alarmButton" class="btn btn-success"><span class="glyphicon glyphicon-time"></span> Set Alarm</button>
		</center>
		<br />
		<div id="selectButton" style="display:none;">
			<center>
				<button onclick="snoozeAlarm();" class="btn btn-warning"><span class="glyphicon glyphicon-pause"></span> Snooze 5 minutes</button>
				<button onclick="stopAlarm();" class="btn btn-danger"><span class="glyphicon glyphicon-stop"></span> Stop Alarm</button>
			</center>
		</div>
	</div>
 
<script src="js/script.js"></script>
</body>
</html>
