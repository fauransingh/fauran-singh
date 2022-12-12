<!DOCTYPE html>
<html>
<head>
<title></title>
	
<script type="text/javascript">
//it is valid only for 10 days

</script>
</head>
<body>

<p id="th"></p>
</body>

<script src="test.js"></script>
</html>
File test.js as described in the video

This is a multiline comment
Author : Harry

document.write("This is an external js2");
document.getElementById('th').innerHTML = "This is a para";

var a1 = 45;
var a11=5;
var a2 = "This is me";
document.write(a1+a11,"<br>");
document.write(a1, a11,"<br>");
console.log("This is console");
console.log is used for debugging purposes

var age = prompt("Tell me your age");
alert("Your age is ", age);

document.write("5 + 9 = ", 5+9,"<br>");
document.write("5 - 9 = ", 5-9,"<br>");
document.write("5 * 9 = ", 5*9,"<br>");
document.write("5 / 9 = ", 5/9,"<br>");
document.write("5 % 9 = ", 5%9,"<br>");

var foodcost = prompt("What is the total amount");
var no = prompt("No of people");
document.write("The total cost of food was ", foodcost, "<br>");
document.write("Each one of you has to pay ", (foodcost/no).toFixed(2),"<br>");


*
document.write("2^9 = ", Math.pow(2,9),"<br>" );
document.write("abs(-34) = ", Math.abs(-34),"<br>");
document.write("sqrt(36) = ", Math.sqrt(36),"<br>");


String Functions

var str1 = "CodeWithHarry";
document.write(str1.length,"<br>" );
document.write(str1.indexOf("With"),"<br>" );
document.write(str1.toLowerCase(),"<br>" );



Relational Operators : ==, !=, <, >, >=
Logical Operators : &&, ||

var age = prompt("What is your age");

if (age<20 && age>=10)
{

	document.write("You go to the school");
}

else if(age<10 && age>3)
{
	document.write("You also go to the school");
}

else
{
	document.write("Do whatever you want");
}



var age = prompt("What is your age?");
switch(age)
{

	case "22":
		document.write("22 years old.. okay");
		break;

	case "21":
		document.write("21 years old.. okay");
		break;
		

	case "12":
		document.write("12 years old.. okay");
		break;
		

	default:
		document.write("default years old.. okay");
		break;			

}


var i =1;
while(i<=100)
{
	document.write(i,"<br>");
	i++;
}


var i =101;
do
{
	document.write(i,"<br>");
	i++;
} while(i<=100)




for (var i = 0; i < 2; i++) {
	document.write(i,"<br>");
}



var books = ["Harry potter", "ncert", "ctci", 65];

document.write(books[3]);



function harry(){

	document.write("We are calling harry");
	console.log("We have executed harry function");


}

harry();
