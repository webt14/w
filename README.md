# Slip 1: Write the HTML code for generating the form as shown below. Apply the
internal CSS to following form to change the font size of the heading to 6pt and change
the color to red and alsochange the background color to yellow.
Solution:
<html>
<head>
<title>slip 1</title>
<style>
body{background-color: yellow;}
table {background-color: turquoise;}
h3 { font-size: 6pt; color:red;}
</style>
</head>
<body>
<center>
<h3> Project Management </h3>
<table border="3" height="200px" width="400px">
<form name=frmlogin><br>
<tr><td>Enter Project Name:</td><td><input type=text name=t1
placeholder=projectname><br><br></td></tr>
<tr><td>Assignned to:</td><td><select name="Names" id="nm" form="frmlogin">
<option value="ross">Ross Geller</option>
<option value="chuck">Chuck Bass</option>
<option value="rachel">Rachel Green </option>
<option value="dan">Dan James</option>
</select></td></tr>
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<tr><td>Start Date:</td><td><input type="date" ></td></tr>
<tr><td>End Date:</td><td><input type="date"> </td></tr>
<tr><td>Priority:</td><br>
<td><input type=radio name=ck value="high">High<br>
<input type=radio name=ck value="avg">Average <br>
<input type=radio name=ck value="low">Low</td></tr>
<tr><td>Description:</td><td><input type=text name="dt"
value="description"></td></tr>
<tr><td><input type=submit value ="submit"></td>
<td><input type=reset value ="clear"></td></tr>
</table>
</center>
</body>
</html>
Slip 2: Create HTML5 page with following specifications
i) Title should be about your City.
ii) Color the background by Pink color.
iii) Place your city name at the top of page in large text and in blue color.
iv) Add names of the landmarks in your city, each in different color, style and font
v) Add any image at the bottom. (Use inline CSS to format the web page)
Solution:
<html>
<head>
<title>PUNE</title>
<body style="background-color:Pink;">
<h3 style="font-size:100px; color:blue;"> PUNE</h3>
<ul>
<li style="color:brown; font-style: italic;">Dagadu Seth Ganpati Temple</li>
<li style="color:red; font-style: oblique;">Saras Baug Temple</li>
<li style="color:purple; font-style: italic;">Phoenix Market City Pune</li>
</ul>
<img src="https://mittalbuilders.com/wp-content/uploads/2020/12/Reasons-to-
settle-down-in-Pune.png" width="200" height="200" align="bottom">
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
</body>
</head>
</html>
Slip 3:
Write a program using html with following CSS specifications-
i. The background colour of the company name should be in green.
ii. The text colour of the company name should be red.
iii. The heading should be large –with font ''comic sans ms''
iv. The description of the company should be displayed in blue color in a
paragraph.
<html>
<head>
<title>Accenture</title></head>
<body style="background-color:#4CBB17">
<h3 style="font-size:60px; color:red; font-style:Comic Sans MS "> Accenture</h3>
<p style=" color:blue; font-size:25px">Accenture plc is an Irish-American professional
services company based in Dublin,
specializing in information technology (IT) services and consulting.<br>
As of 2022,Accenture is considered
the largest consulting firm in the world by number of employees.<br>
Accenture is a $61.6-billion-in-annual-revenue technology and consulting company
incorporated in Dublin, Ireland.
Led by Chair & CEO Julie Sweet, who prior to her promotion in 2019 served as CEO of
Accentures business in North America,
the Fortune Global 500 information technology services company has supplemented its
growth
through high-profile acquisitions like that of ad agency Droga5. With 721,000 people
worldwide</p>
</html>
Slip4: Write a HTML code, which generate the following output
List of Books
Item No Item Name Price
Rs. Paise
1 Programming in Python 500 50
2 Programming in Java 345 00
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<html>
<body>
<table border = 1>
<caption>list of book </caption>
<tr>
<td rowspan=2>item no </td>
<td rowspan=2>Item name </td>
<td colspan=2 > price
<tr>
<td >Rs </td>
<td >paise</td>
</td>
</tr>
</tr>
<tr>
<td>1</td>
<td>programming in python </td>
<td>500</td><td>50</td>
</tr>
<tr>
<td>2</td>
<td>programming in java </td>
<td>345</td><td>00</td>
</tr>
</body>
</html>
Slip5: Create following Bootstrap Web Layout Design and change Title, add your
personal information, educational information, job profile.
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<html lang="en">
<head>
<title>NR Class</title>
<link rel="stylesheet" href="bootstrap.min.css">
</head>
<body>
<div class="jumbotron">
<center><h1>My First Bootstrap Page</h1></center>
<center><p>This is responsive</p></center>
</div>
<div class="row">
<div class="col-3 offset-1 bg-light">
<h4>Personal Information</h4>
<p>name</p>
</div>
<div class="col-3 offset-1 bg-light">
<h4>Educational Information</h4>
<p>name</p>
</div>
<div class="col-3 offset-1 bg-light">
<h4>Job Profile</h4>
<p>name</p>
</div>
</div>
</body>
</html>
Slip 6: Create following Bootstrap Web Layout Design and set Header background color
Blue, add your College name, set Menu section background color green create menu About
Us, In content section add college information, background color yellow, Footer section
backgroundcolor red, add address of college.
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<html>
<head>
<link rel="stylesheet" href="bootstrap.min.css">
<title>NRC</title>
</head>
<body>
<div class="row ">
<div class="col-12 bg-primary">
<h3>header</h3>
</div>
</div>
<div class="row">
<div class="col-4 bg-info">
<h4>Menu</h4>
</div>
<div class="col-8 bg-warning ">
<p>this is collge information</p>
</div>
</div>
<div class="row">
<div class="col-12 bg-danger">
<h3>Footer</h3>
</div>
</div>
</body>
</html>
Slip7 Design HTML 5 Page Using CSS Which Displays the following Navigation Bar
<html>
<head>
<title>Navigation Bar</title>
<style>
li {
display:inline;
}
</style>
</head>
<body style="font-size:40px">
<ul>
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<li><a href="HOME.asp" style="color:white; background-
color:grey;">HOME</a></li>
<li> <a href="JAVA.asp" style="color:blue; background-
color:#D3D3D3;">Java</a></li>
<li ><a href="HTML.asp" style="color:blue; background-
color:#D3D3D3;">HTML</a></li>
<li><a href="CSS.asp" style="color:blue; background-
color:#D3D3D3;">CSS</a></li>
</ul>
</body>
</html>
Slip8: Design an HTML form to accept two strings from the user. Write a PHP script for
thefollowing.
a. Find whether the small string appears at the start of the large string.
b. Find the position of the small string in the big string.
c. Compare both the string for first n characters, also the comparison should not be case
sensitive.
HTML FILE
<html>
<body>
<form action="slip_8.php" method="get">
enter first string:<input type="text" name="str1"><br>
enter second string:<input type="text" name="str2"><br>
<input type="submit" value="submit">
</form>
</body>
</html>
PHP FILE
<?php
$a=$_GET["str1"];
$b=$_GET["str2"];
//$len1=strlen($a);
//$len2=strlen($b);
echo "Length $len1 $len2";
$pos=strpos($a,$b);
if($pos==0)
{
echo"the small string appears at the start of the large string<br>";
}
else
{
echo"small string does not appear at the start of the large string<br>";
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
}
$pos=strpos($a,$b);
echo"the small string appears at $pos position<br>";
if(strcasecmp($a,$b)==0)
echo "Both Strings are equal<br>";
else if(strcasecmp($a,$b)>0)
echo "first string bigger<br>";
else
echo "second string is bigger<br>";
?>
Slip9: Write a PHP script for the following: Design a form having a text box and a drop
down listcontaining any 3 separators(e.g. #, |, %, @, ! or comma) accept a strings from the
user and also aseparator.
a. Split the string into separate words using the given separator.
b. Replace all the occurrences of separator in the given string with some other separator.
c. Find the last word in the given string.
HTML FILE
<html>
<body>
<form action="slip_9.php"method="get">
Enter a string:<input type="text" name="str1"><br>
choose a label
<select name="sep" id="sep">
<option value="#">#</option>
<option value="!">!</option>
<option value="@">@</option>
</select><br>
<input type="radio" name="op" value="a">Split The String Using The Seperator<br>
<input type="radio" name="op" value="b">Replace The Occurences Of The
Seperator With Another Seperator<br>
<input type="radio" name="op" value="c">Find The Last Word Of The String<br>
<input type="submit"value="submit">
</form>
</body>
</html>
PHP FILE
<?php
$str=$_GET['str1'];
$sep=$_GET['sep'];
$op=$_GET['op'];
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
//echo "$str $sep $op";
switch($op)
{
case 'a':$m=explode($sep,$str);
foreach($m as $a){
echo "$a<br>";
}
break;
case 'b':
$cnt=substr_count($str,$sep);
$n=str_replace($sep,"!",$str,$cnt);
echo "After changing separators<br>";
echo $n;
break;
case 'c':$ar=explode(" ",$str);
$cnt=count($ar);
echo "This is the last word : ".$ar[$cnt-1];
break;
}
?>
Slip10: Write a script to accept two integers(Use html form having 2
textboxes).Write a PHP script to,
a. Find mod of the two numbers.
b. Find the power of first number raised to the second.
c. Find the sum of first n numbers (considering first number as n)
d. Find the factorial of second number.
(Write a separate function for each of the above operations.)
HTML FILE
<html>
<head>
<title>Assignment 3 Q1</title>
</head>
<body>
<form action="slip10.php" value="GET">
Enter Two Numbers<br>
<input type="text" name="n1"><br><br>
<input type="text" name="n2"><br><br>
Select An Operation<br>
<input type="radio" name="op" value="mod">Mod Of The Two Numbers<br><br>
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<input type="radio" name="op" value="power">Power Of The First Number Raised
To The Second<br><br>
<input type="radio" name="op" value="sum">The Sum Of First n Numbers<br><br>
<input type="radio" name="op" value="fact">Factorial Of The Second
Number<br><br>
<input type="submit" value="Submit">
</form>
</body>
</html>
PHP FILE
<?php
$n1=$_GET["n1"];
$n2=$_GET["n2"];
$op=$_GET["op"];
function mod($n1,$n2)
{
$n3=0;
if($n2!=0)
$n3=$n1%$n2;
return $n3;
}
function power($n1,$n2)
{
$n3=1;
for($i=1;$i<=$n2;$i++)
$n3=$i*$n1;
return $n3;
}
function sum($n1)
{
$n3=0;
for($i=1;$i<=$n1;$i++)
{
$n3=$n3+$i;
}
return $n3;
}
function fact($n2)
{
$n3=1;
for($i=1;$i<=$n2;$i++)
{
$n3=$n3*$i;
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
}
return $n3;
}
switch($op)
{
case "mod": $result=mod($n1,$n2);
echo "Mod of $n1 and $n2 is $result.";
break;
case "power":$result=power($n1,$n2);
echo "$n1 raised to $n2 is $result.";
break;
case "sum": $result=sum($n1);
echo "Sum of first $n1 number is $result.";
break;
case "fact":$result=fact($n2);
echo"Factorial of $n2 is $result.";
break;
}
?>
Slip11: Create a button with different style (Secondary, Primary, Success, Error, Info,
Warning, Danger) using BootStrap.
<html>
<head>
<link rel=stylesheet href="bootstrap.min.css">
</head>
<body>
<form >
<input type= button value="primary" class="btn btn-primary">
<input type= button value="warning" class="btn btn-warning">
<input type= button value="secondary"class="btn btn-Secondary">
<input type= button value="success" class="btn btn-success">
<input type= button value="info" class="btn btn-info">
<input type= button value="danger" class="btn btn-danger">
</body>
</html>
Slip12: Write a PHP script for the following: Design a form to accept two numbers from the
user. Give options to choose the arithmetic operation (use radio buttons). Display the result
on the nextform. (Use the concept of function and default parameters. Use ‘include’ construct
or require statement)
PHP FILE
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<?php
$x=$_POST['s1'];
$y=$_POST['s2'];
$op=$_POST['op'];
function add($x=4,$y=2)
{
$result=$x+$y;
echo"adition is $result";
}
function sub($x=4,$y=2)
{
$result=$x-$y;
echo"subtraction is $result";
}
switch ($op)
{
case"1": add($x,$y);
break;
case"2": sub($x,$y);
break;
}
?>
HTML FILE
<html>
<body>
<form action="slip12in.php"method="POST">
first number
<input type=text name=s2><br>
second number
<input type=text name=s1><br>
chose opration from below<br>
addition
<input type=radio value="1" name=op> <br>
subtraction
<input type=radio value="2"name=op> <br>
<input type= submit value="submit"><br>
</body>
</html>
PHP FILE
<?php
include'slip12.php';
?>
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
Slip13: Write a PHP script to create a chess board using CSS on table cells.
<html>
<head>
<head><title>NRC ChessBoard</title>
<style>
.clr1
{
background-color:black;
}
.clr2
{
background-color:white;
}
table
{
width:100%;
height:100%;
}
</style>
<?php
echo"<table border=1>";
for($i=1;$i<=8;$i++)
{
echo"<tr>";
if($i%2==0)
{
for($j=1;$j<=8;$j++)
{
if($j%2==1)
echo"<td class=clr2></td>";
else
echo"<td class=clr1></td>";
}
}
else
{
for($j=0;$j<8;$j++)
{
if($j%2==0)
echo"<td class=clr1></td>";
else
echo"<td class=clr2></td>";
}
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
}
echo "</tr>";
}
echo"</table>" ;
?>
</html>
Slip14: Create a container add row inside it and add 3 columns inside row using BootStrap.
<html>
<head>
<link rel="stylesheet" href="bootstrap.min.css">
</head>
<body>
<div class=container>
<div class="row bg-light" >
<div class="col-4">col1
</div>
<div class="col-4">col2
</div>
<div class="col-4">col3
</div>
</div>
</div>
</body>
</html>
Slip15: Design a form to accept string from the user and perform the following operations
a. To select first 5 words from the string
b. Convert the given string to lowercase and then to Title case.
c. Pad the given string with “*” from left and right both the sides.
d. Remove the leading whitespaces from the given string.
e. Find the reverse of given string.
HTML FILE
<html>
<body>
<form action="Slip15.php" method=get>
Enter a String<input type=text name=t1><br>
<input type=radio name=op value=1>Select 5 words<br>
<input type=radio name=op value=2>LowerCase<br>
<input type=radio name=op value=3>Padding<br>
<input type=radio name=op value=4>Remove Spaces<br>
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<input type=radio name=op value=5>Reverse<br><br>
<input type=submit value=submit>
</form>
</body>
</html>
PHP FILE
<?php
$str=$_GET['t1'];
$ch=$_GET['op'];
if($ch==1)
{
$ar=explode(" ",$str,6);
foreach($ar as $a)
echo "$a<br>";
}
else if($ch==2)
{
$str=strtolower($str);
echo $str;
$str=ucwords($str);
echo "<br>$str";
}
else if($ch==3)
{
$str=str_pad($str,20,"*",STR_PAD_BOTH);
echo $str;
}
else if($ch==4)
{
$str=trim($str);
echo $str;
}
else if($ch==5)
{
$str=strrev($str);
echo $str;
}
?>
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
Slip16: Write a PHP script for the following: Design a form to accept the marks of 5
different subjects of a student, having serial number, subject name & marks out of 100.
Display theresult in the tabular format which will have total, percentage and grade. Use only
3 text boxes.(Use array of form parameters)
HTML FILE
<html>
<head>
<title> marksheet </title>
</head>
<body>
<form name = "string" action = "slip16.php" method = "get">
student id <input type = "text" name = "v1"/></br></br>
Subject name<input type = "text" name = "v2"/></br></br>
subject marks<input type = "text" name = "v3"/></br></br>
<button type = "submit"> display marklist </button>
</form>
</body>
</html>
PHP FILE
<?php
$a =$_GET['v1'];
$b =$_GET['v2'];
$c =$_GET['v3'];
$sum=0;
echo "<h1> <center>Marksheet</center></h1>";
echo "<h3><center>student id:$a</h3><br>";
$d =explode(",",$b);
$e =explode(",",$c);
echo "<center><table border=2 width=50%>";
for($i=0;$i<=4;$i++)
{
echo "<tr>
<td>$d[$i]</td>
<td>$e[$i]</td>
</tr>";
$sum=$e[$i]+$sum;
}
$result=$sum/5;
echo "<tr><td>Total marks </td><td>$sum</td>";
echo"<tr><td>Percentage</td><td>$result</td></tr>";
echo "</center>"
?>
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
Slip17: Write a PHP script to sort the following associative array :
array(“Sagar"=>"31","Vicky"=>"41","Leena"=>"39","Ramesh"=>"40") in
a) ascending order sort by Value
b) ascending order sort by Key
c) descending order sorting by Value
d) descending order sorting by Key
<?php
$a = array("Sagar"=>"31","Vicky"=>"41","Leena"=>"39","Ramesh"=>"40");
echo "sorting in ascending order by value<br>";
asort($a);
print_r($a);
echo "sorting in ascending order by key<br>";
ksort($a);
print_r($a);
echo "sorting in decending order by value<br>";
arsort($a);
print_r($a);
echo "sorting in decending order by key<br>";
krsort($a);
print_r($a);
?>
Slip18: Write a menu driven program to perform the following operations on an associative
array
a. Reverse the order of each element’s key-value pair.
b. Traverse the element in an array in random order.
c. Convert the array elements into individual variables.
d. Display the elements of an array along with key.
HTML FILE
<html>
<head>
<title> String operations </title>
<body>
<form name = "String" action = "s18_q1.php" method = "get">
<h2> Select Operations</h2>
<input type = "radio" name ="s" value=1>Reverse the order</br></br>
<input type = "radio" name ="s" value=2>Traverse the element</br></br>
<input type = "radio" name ="s" value=3>Convert the array elements</br></br>
<input type = "radio" name ="s" value=4>Display the elements of an array along with
key.</br></br>
<input type=submit value=send>
</body>
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
</html>
PHP FILE
<?php
$a = array("a"=>1,"b"=>21,"c"=> 56);
switch($_GET['s'])
{
case 1:
echo "Orginal Array is <br>";
print_r($a);
echo "reverse Array is <br>";
$c =array_reverse($a);
print_r($c);
break;
case 2:
echo "Orginal Array is <br>";
print_r($a);
echo "traversing Array is <br>";
foreach($a as $v)
echo "$v<br>";
break;
case 3:
echo " Original array is<br>";
print_r($a);
echo "elements into individual variables<br>";
$e = extract($a);
print_r($e);
break;
case 4:
echo " Original array is<br>";
print_r($a);
echo "key value pair is<br>";
foreach ($a as $k=>$v)
{
print_r("$k=>$v");
echo"<br>";
}
break;
default:
echo "Invalid choice!!";
}
?>
Slip19: Write a PHP script to accept 2 strings from the user, the first string should be a
sentence andsecond can be a word.
a. Delete a small part from first string after accepting position and number of
characters toremove.
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
b. Insert the given small string in the given big string at specified position without
removingany characters from the big string.
c. Replace some characters/ words from given big string with the given small string at
specified position.
HTML FILE
<html>
<form action=slip19.php method=get>
Enter a Sentence<input type=text name=t1><br>
Enter a word<input type=text name=t2><br>
Enter position<input type=text name=t3><br>
Enter number of characters to remove<input type=text name=t4><br>
<input type=submit value="Display Result">
</form>
</html>
PHP FILE
<?php
$st=$_GET['t1'];
$wd=$_GET['t2'];
$ps=$_GET['t3'];
$nr=$_GET['t4'];
$dup_st=$st;
$str=substr_replace($st,"",$ps,$nr);
echo "<br>$str<br>";
$str=substr_replace($st,$wd,$ps,0);
echo "<br>$str<br>";
$str=substr_replace($st,$wd,$ps,strlen($wd));
echo "<br>$str<br>";
?>
Slip20: Write a menu driven program to perform the following operations on associative
arrays:
a) Split an array into chunks
b) Sort the array by values without changing the keys.
c) Filter the even elements from an array.
HTML FILE
<html>
<body>
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<form action="slip20.php" method="GET">
Enter Your Choice:<br>
<input type="radio" name="ch" value=1> Split an array into chunks<br>
<input type="radio" name="ch" value=2> Sort array by values without changing key
values <br>
<input type="radio" name="ch" value=3> Filter even elements from array <br>
<input type="submit" value="Submit">
</form>
</body>
</html>
PHP FILE
<?php
$choice=$_GET['ch'];
$arr=array('a'=>1,'b'=>20,'c'=>13,'d'=>5,'e'=>18,'f'=>12,'g'=>7,'h'=>8,'i'=>15,'j'=>10);
switch($choice)
{
case 1:
print_r(array_chunk($arr,2));
break;
case 2:
asort($arr);
echo "Array in ascending order:<br>";
print_r($arr);
break;
case 3:
function even($var)
{
return $var%2==0?1:0;
}
$br=array_filter($arr,"even");
print_r($br);
break;
}
?>
Slip21: Create an array of 15 high temperatures, approximating the weather for a spring
month, then find the average high temp, the five warmest high temps Display the result on the
browser
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<?php
$temp_array=range(31,45);
$tot_temp = 0;
$count = count($temp_array);
echo "Total temp values are: ".$count;
foreach($temp_array as $temp)
{
$tot_temp += $temp;
}
$avg_high_temp = $tot_temp/$count;
echo "<br> Average Temperature is : ".$avg_high_temp."
";
sort($temp_array);
echo " <br> List of five lowest temperatures :";
$res1= array_slice($temp_array,0,5);
foreach($res1 as $high_temp)
{
echo "<br> $high_temp";
}
echo "<br> List of five highest temperatures :";
$res1= array_slice($temp_array,10);
foreach($res1 as $high_temp)
{
echo "<br> $high_temp";
}
?>
Slip22: Write a menu driven program to perform the following queue related operations
a) Insert an element in queue
b) Delete an element from queue
c) Display the contents of queue
HTMl FILE
<html>
<body>
<form method=get action="slip 23.php">
<input type=radio name=ch value=1> Insert in queue<br>
Enter No to insert<input type=text name=n1><br>
<input type=radio name=ch value=2> Delete in queue<br>
<input type=radio name=ch value=3> Display<br>
<input type=submit>
</form>
</body>
</html>
PHP FILE
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
<?php
$stk=array(1,2,3,4,5);
$ch=$_GET['ch'];
else if($ch==1)
{
echo "Insert element in queue <br>";
$n4=$_GET['n4'];
array_push($stk,$n4);//Insert element at last
print_r($stk);
}
else if($ch==2)
{
echo "Delete element from queue. <br>";
$res=array_shift($stk); //at begining
echo "Deleted element is:".$res;
}
else if($ch ==3)
{
echo"Given array is: <br>";
print_r($stk);
}
?>
Slip23: Write a menu driven program to perform the following stack related operations:
a) Insert an element in stack
b) Delete an element from stack
c) Display the contents of stack
HTML FILE
<html>
<body>
<form method=get action="slip23.php">
<input type=radio name=ch value=1> Insert in stack<br>
Enter No to insert<input type=text name=n1><br>
<input type=radio name=ch value=2> Delete in stack<br>
<input type=radio name=ch value=3> Display<br>
<input type=submit>
</form>
</body>
</html>
PHP FILE
<?php
$stk=array(1,2,3,4,5);
$ch=$_GET['ch'];
if($ch==1)
{
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
echo "Insert element in stack <br>";
$n1=$_GET['n1'];
array_push($stk,$n1); //at end
print_r($stk);
}
else if($ch==2)
{
echo "Delete element in stack <br>";
array_pop($stk);
print_r($stk);
}
else if($ch == 3)
{
echo"Given array is: <br>";
print_r($stk);
}
?>
Slip24: Write a PHP program to read two file names from user and append content of first
file intosecond file.
HTML FILE
<html lang="en">
<head>
<title>NRC File Handling</title>
</head>
<body>
<form action="slip24.php" method="get">
Enter File name to read <input type="text" name="fname1">
Enter File name to write <input type="text" name="fname2">
<input type="submit" value="Copy">
</form>
</body>
</html>
PHP FILE (create 2 text file pf your choice name and use same)
<?php
$fname1=$_GET['fname1'];
$fname2=$_GET['fname2'];
$fp1=fopen($fname1,"r");
$fp2=fopen($fname2,"a");
$size=filesize($fname1);
$str=fread($fp1,$size);
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
fwrite($fp2,$str,$size);
echo "Append Successfull";
?>
Slip25: Write a menu driven program to perform various file operations. Accept
filename from user.
a) Display type of file.
b) Display last modification time of file
c) Display the size of file
d) Delete the file
HTML FILE
<html lang="en">
<head>
<title>Document</title>
</head>
<body>
<form action="slip25.php" method="get">
Enter File name to read <input type="text" name="fname1"><br>
<input type="radio" name="op" value="1">Display Type of File<br>
<input type="radio" name="op" value="2">Display Modification Time<br>
<input type="radio" name="op" value="3">Display File Size<br>
<input type="radio" name="op" value="4">Delete File<br>
<input type="submit" value="Copy">
</form>
</body>
</html>
PHP FILE
<?php
$fp=$_GET['fname1'];
$op=$_GET['op'];
switch($op)
{
case 1:
echo basename($fp);
break;
case 2: $mtime=stat($fp);
echo Date("d/M/Y h:m:s",$mtime['mtime']);
break;
case 3:echo filesize($fp);
break;
case 4:unlink($fp);
echo "File deleted";
break;
}
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
?>
Slip 26: Consider the following entities and their relationship.
Doctor ( doc_no, dname, address ,city ,area)
Hospital (hosp_no, hname, hcity)
Doctor-Hospital related with many-one
relationship. Create a RDB in 3NF for above and
solve the following.
Using above database write a script in PHP to print the Doctor visiting to the Hospital in
tabularformat. Accept Hospital name from user.
(Use your database)
Solution
Html file
<html>
<form action=slip26.php method=get>
Enter Hospital Name<input type=text name=t1><br>
<input type=submit value="Display Doctors">
</form>
</html>
PHP File
<?php
$con=pg_connect("host=localhost user=postgres password=nrc dbname=slip26");
$cn=$_GET['t1'];
$rs=pg_query($con,"select * from doctor,hospital where hname='$cn' and hsno=hno");
while($row=pg_fetch_array($rs))
{
echo "Id:$row[0] Name:$row[1] Address:$row[2] City:$row[3]
Pin:$row[4]<br>";
}
?>
Slip27: Write a PHP program to read two file names from user and copy the content of first
file into second file.
HTML FILE
<html lang="en">
<head>
<title>NRC File Handling</title>
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
</head>
<body>
<form action="slip27.php" method="get">
Enter File name to read <input type="text" name="fname1">
Enter File name to write <input type="text" name="fname2">
<input type="submit" value="Copy">
</form>
</body>
</html>
PHP FILE
<?php
$fname1=$_GET['fname1'];
$fname2=$_GET['fname2'];
$fp1=fopen($fname1,"r");
$fp2=fopen($fname2,"w");
$size=filesize($fname1);
$str=fread($fp1,$size);
fwrite($fp2,$str,$size);
echo "Append Successfull";
?>
Slip28: Write a program to read a flat file “student.dat”, calculate the percentage and
display the data from file in tabular format.(Student.dat file contains rollno, name, OS, WT,
DS, Python, Java, CN )
Student.dat file
rollno name OS WT DS Python Java CN
1 Abd 30 30 25 23 20 45
2 xyz 32 33 24 25 25 45
PHP FILE
<?php
$fp=fopen("student.dat","r");
$ar=fscanf($fp,"%s%s%s%s%s%s%s%s",$rl,$nm,$os,$wt,$ds,$py,$jv,$cn);
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
echo "<table
border=1><tr><th>$rl</th><th>$nm</th><th>$os</th><th>$wt</th><th>$ds</th><t
h>$py</th><th>$jv</th><th>$cn</th><th>Percentage</tr>";
while(($ar=fscanf($fp,"%s%s%d%d%d%d%d%d",$rl,$nm,$os,$wt,$ds,$py,$jv,$cn))!=f
alse)
{
$total=$os+$wt+$ds+$py+$jv+$cn;
$per=$total/6;
echo
"<tr><th>$rl</th><th>$nm</th><th>$os</th><th>$wt</th><th>$ds</th><th>$py</t
h><th>$jv</th><th>$cn</th><td>$per</td></tr>";
}
echo "</table>";
?>
Slip29:
Consider the following entities and their relationships
Event (eno , title , date )
Committee ( cno , name, head , from_time ,to_time , status)
Event and Committee have many to many relationship. Write a php script to accept title of
eventand modify status committee as working
HTML File
<html>
<form action=slip29.php method=get>
Enter Event Name:<input type=text name=t1><br>
<input type=submit value="Change Status">
</form>
</html>
PHP File
<?php
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
$con=pg_connect("host=localhost user=postgres password=nrc bname=practicals22");
//echo $con;
$en=$_GET['t1'];
$ws='Working';
$x=pg_query($con,"update comm_mem set cstatus='$ws' from event_comm,event
where comm_mem.cno=event_comm.cno and event_comm.eno=event.eno and
etitle='$en'");
if($x>0)
echo "Working status updated";
else
echo "Status not updated";
?>
Slip30:
Consider the following entities and their relationships
Student (Stud_id,name,class)
Competition (c_no,c_name,type)
Relationship between student and competition is many-many with attribute rank and year.
Createa RDB in 3NF for the above and solve the following. Using above database write a
script in PHPto accept a competition name from user and display information of student
who has secured 1st rank in that competition.
HTML File
<html>
<form action=slip30.php method=get>
Enter Comp. Name<input type=text name=t1><br>
<input type=submit value="Display Ranker">
</form>
</html>
PHP File
<?php
$con=pg_connect("host=localhost user=postgres password=nrc dbname=slip30");
$cn=$_GET['t1'];
MOBILE: 9730381255 | WWW.NRCLASSESPUNE.COM | WWW.BCSBCA.COM
$rs=pg_query($con,"select * from student,competition,stud_comp where cname='$cn'
and srank=1 and id=sid and competition.cno=stud_comp.cno");
while($row=pg_fetch_array($rs))
{
echo "$row[0] $row[1] $row[2]<br>";
}
?>
