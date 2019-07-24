<?php
$host="localhost";
$user="root";
$pass="";
$data="register";
$conn=mysqli_connect($host,$user,$pass,$data);

$sql = "SELECT * FROM registernew";
$result = $conn->query($sql);
if ($result->num_rows > 0) {
while($row = $result->fetch_assoc()) {
echo"Seller Name:" . $row["sname"]. "&emsp;Address: " . $row["adres"]. "&emsp;City:" . $row["city"]."&emsp;Phone Number:".$row["phnum"]."&emsp;Email:".$row["email"]."&emsp;Vehicle Make:".$row["vehmke"]."&emsp;Vehicle Model:".$row["vehmod"]."&emsp;Vehicle Year:".$row["vehyr"]."<br>"; 

}}
else {
echo "0 Result";
}
?>
