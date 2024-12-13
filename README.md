# SoalBarnameNevisiBarnameNevisiSoal.php
https://quera.org/problemset/3408?tab=description
<?php
$n = (int)readline("Enter a number: ");
$m = (string)readline("Enter n words:");
$a = explode(" ", $m);
$q = $n - 1;
for($i = $q; $i >= 0; $i--){
	echo $a[$i] . " ";
}
