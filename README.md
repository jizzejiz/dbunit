# dbunit
<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="css/register1.css">
	<title>USER REGISTRATION</title>
</head>
<form method="POST"action="regis.php">
<body>
	<table>
		<tr>
			<td>
				SELLER NAME : 
			</td>
			<td>
				<input type="text" name ="name" required>
			</td>
		</tr>
		<tr>
			<td>
				ADDRESS :
			</td>
			<td>
				<input type="text" name="address" required>
			</td>
		</tr>
		<tr>
			<td>
				CITY
			</td>
			<td>
				<input type="text" name="city" required>
			</td>
		</tr>
		<tr>
			<td>
				PHONE NUMBER
			</td>
			<td>
				<input type="text" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" name="phone" required>
			</td>
		</tr>
			<td>
				EMAIL ADDRESS
			</td>
			<td>
				<input type="text" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$" name="email" required>
			</td>
		</tr>
		<tr>
			<td>
				VEHICLE MAKE 
			</td>
			<td>
				<input type="text" name="make" required>
			</td>
		</tr>
		<tr>
			<td>
				Model
			</td>
			<td>
				<input type="text" name="model" required>
			</td>
		</tr>
		<tr>
			<td>
				YEAR
			</td>
			<td>
				<input type="text" name="year" required>
			</td>
		</tr>
		<tr>
			<td>
				<button type="submit"  name="submit">Submit it</button><br><br>
				<button type="submit"><a href="http://localhost/display.php">Search</a></button>
			</td>
		</tr>
	</table>
</body>
</form>
</html>
