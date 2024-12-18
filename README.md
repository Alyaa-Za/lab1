<!-- array_count -->
<!-- <?php 
$array = array(1,2,3,4);
echo count($array);
?> -->

<!-- array_merge -->
<!-- <?php
$array1 = array("color" => "red",2,4);
$array2 =array("a","b","color"=>"green","shape"=>"trapezoid",4);
$result =array_merge($array1,$array2);
print_r($result);
?> -->
<!-- array_ push-->
<!-- <?php
$array3 =array("red","green");
array_push($array3,"blue","yellow");
print_r($array3);
?> -->
<!-- array_differ -->
<!-- <?php
$array4 =array("a"=>"green","b"=>"brown","c"=>"blue","red");
$array5 =array("a"=>"green","yellow","red");
$result2=array_diff($array4,$array5);
print_r($result2);
?> -->
<!-- array_intersect -->
<!-- <?php
$array6 =array("a"=>"green","b"=>"brown","c"=>"blue","red");
$array7 =array("a"=>"green","yellow","red");
$result3=array_intersect($array4,$array5);
print_r($result3);
?> -->
<!-- array_slice -->
<!-- <?php
$input =array("a","b","c","d","e");
$output =array_slice($input,2);
print_r($output);
?> -->




<!-- السلاسل النصية -->
<!-- strlen -->
<!-- <?php
$str = "Hello, World!";
echo strlen($str); // Output: 13
?> -->

<!-- strpos -->
<!-- <?php
$mystring = "Hello, World!";
$findme = "World";
$pos = strpos($mystring, $findme);
echo $pos; // Output: 7
?> -->

<!-- str_replace -->
<!-- <?php
$phrase  = "You should eat fruits, vegetables, and fiber every day.";
$healthy = array("fruits", "vegetables", "fiber");
$yummy   = array("pizza", "beer", "ice cream");

$newphrase = str_replace($healthy, $yummy, $phrase);
echo $newphrase;
?> -->

<!-- strtoupper -->
<!-- <?php
$str = "Hello, World!";
echo strtoupper($str); 
?> -->

<!-- strtolower -->
<!-- <?php
$str = "Hello, World!";
echo strtolower($str); 
?> -->

<!-- substr -->
<!-- <?php
$str = "Hello, World!";
echo substr($str, 7, 5); 
?> -->
