# php-for-loop-even-odd
<?php
/* php loop, while loop, for loop, for each loop, do while loop;
while()
	statement; */
$a=1;
while($a<="12"){
	
	if($a==12){
		echo $a.".";
	}else{
		echo $a.".";
	}
	echo "php tutorial"."<br>";
	$a++;
}


//odd number:1,3,5,7,9,11 //even number: 2,4,6,8,10,12
for($x=2; $x<=12; $x++){
	if($x%2==0){
		echo $x." even";
	}else{
	echo $x." odd";	
	}
	echo $x."<br>";
}
?>
