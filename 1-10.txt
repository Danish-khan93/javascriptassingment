// chapter 1
alert("Good Morning Danish");
alert("Error! Please Enter a valid password");
alert("wellcome to js land...\nHappy coding!");
alert("Wellcome to JS land...");
alert("Happy Coding!");

// chapter 2

var userName;
var myName = "Danish khan";
var message;
message = "Hello world";
alert(message);
var studentName = "Danish khan";
var age = 30;
var courseName = "Mobile web and app developer";
alert(studentName);
alert(age);
alert(courseName);
var message = "pizza\npizz\npiz\npi\np";
alert(message);
var email = "danishshoukat1993@gmail.com";
alert("My email is " + email);
var book = "A smarter way to learn JavaScript";
alert("I am trying to learn from the book of " + book);
var message = "Yeh! i can write HTML content through JS";
document.write(message);
alert("▬▬▬▬▬▬▬▬▬ஜ۩۞۩ஜ▬▬▬▬▬▬▬▬▬");

// chapter 3
var age = 30;
alert("I am " + age + " year old");
var numOfVisit = 14;
alert("you are visit " + numOfVisit + " times");
var birthYear = 1993;
document.write(
  "my birth year is" + birthYear + "<br> the data type i decleared in number"
);
var customerName = "danish khan";
var order = "bed";
var storeName = "xyz store";
document.write(customerName + " ordered " + order + " on " + storeName);

// chapter 4

var myName;
var herName;
var hisName;
var myName;
var $myName;
var _myName;
var myName10;
var my$Name10;
// var 1my$Name10;
// var /y$Name10;
// var -y$Name10;
// var .y$Name10;
document.write("<h1>Rules for naming JS variables</h1>");
document.write("variable name only contain $_ in starting and mid and number");

// chapter 5

var num1 = 4;
var num2 = 5;
var total1 = num1 + num2;
var total2 = num1 - num2;
var total3 = num1 * num2;
var total4 = num1 / num2;
var total5 = num1 % num2;

document.write(total1 + "<br>");
document.write(total2 + "<br>");
document.write(total3 + "<br>");
document.write(total4 + "<br>");
document.write(total5 + "<br>");

var num;
document.write(num + "<br>");
num = 5;
document.write(num + "<br>");
++num;
document.write(num + "<br>");
num += 7;
document.write(num + "<br>");
--num;
document.write(num + "<br>");
num %= 3;
document.write(num + "<br>");

var ticketPrice = 600;
var buying = 5;
document.write(ticketPrice * buying);

// table
document.write("table of 4 <br>");
var table = 4;
document.write(table + " X 1 = " + table * 1 + " <br> ");
document.write(table + " X 2 = " + table * 2 + " <br> ");
document.write(table + " X 3 = " + table * 3 + " <br> ");
document.write(table + " X 4 = " + table * 4 + " <br> ");
document.write(table + " X 5 = " + table * 5 + " <br> ");
document.write(table + " X 6 = " + table * 6 + " <br> ");
document.write(table + " X 7 = " + table * 7 + " <br> ");
document.write(table + " X 8 = " + table * 8 + " <br> ");
document.write(table + " X 9 = " + table * 9 + " <br> ");
document.write(table + " X 10 = " + table * 10 + " <br> ");

// temperature converter start

var tempInCelsius = 25;
// convert celsius in fahrenheit
var inFahrenheit = tempInCelsius * (9 / 5) + 32;
document.write(
  tempInCelsius + " <sup>o</sup> C is " + inFahrenheit + " <sup>o</sup> F  <br>"
);

//     // convert fahrenheit in celsius
var tempInFahrenheit = 70;
var inCelsius = (tempInFahrenheit - 32) * (5 / 9);
document.write(
  tempInFahrenheit + " <sup>o</sup> F is " + inCelsius + " <sup>o</sup> C  <br>"
);
// temperature converter end

// e-commerce program start
document.write("<h1>Shopping Cart</h1> <br>");
var priceOfItem1 = 650;
var toatalQuantityOfItem1 = 3;
var priceOfItem2 = 100;
var toatalQuantityOfItem2 = 7;
var shippingCharges = 100;
document.write("Price of item 1 " + priceOfItem1 + "<br>");
document.write("Quantity of item 1 " + toatalQuantityOfItem1 + "<br>");
document.write("Price of item 2 " + priceOfItem2 + "<br>");
document.write("Quantity of item 2 " + toatalQuantityOfItem2 + "<br>");
document.write("Shipping Charges is " + shippingCharges + "<br>");
var totalCostOfOrder =
  priceOfItem1 * toatalQuantityOfItem1 +
  priceOfItem2 * toatalQuantityOfItem2 +
  shippingCharges;
document.write("Total cost of your order is " + totalCostOfOrder);

// e-commerce program end
document.write("<h1>MARKS SHEET</h1> <br>");

// mark sheet program start
var totalMarks = 980;
var obtainMarksStudent = 804;
var percentage = (obtainMarksStudent / totalMarks) * 100;

document.write("Total Marks: " + totalMarks + "<br>");
document.write("Marks obtained: " + obtainMarksStudent + "<br>");
document.write("Percentage: " + percentage + "<br>");

// mark sheet program end

// currency in pk start
document.write("<h1>Currency in PKR</h1> <br>");
var currencyInPkr = 10 * 104.8 + 25 * 28;
document.write("Total Currency in PKR: " + currencyInPkr);
// currency in pk end

// question num 10

var num = 10;
console.log(((num + 5) * 10) / 2);

// age calculator start

document.write("<h1>Age Calculator</h1> <br>");
var currentYear = 2023;
var birthYear = 1993;
var age = currentYear - birthYear;
document.write("current year " + currentYear + "<br>");
document.write("Birth year " + birthYear + "<br>");
document.write("Your age is " + age + "<br>");

// age calculator end

// geometrizer program start

document.write("<h1>The Geometrizer</h1>");
var radiusOfCircle = 20;
var circumferenceOfCircle = 2 * 3.142 * radiusOfCircle;
var areaOfCircle = 3.142 * radiusOfCircle ** 2;
document.write("The radius of circle >" + radiusOfCircle + "<br>");
document.write("The Circumference is : " + circumferenceOfCircle + "<br>");
document.write("The area of Circle is :" + areaOfCircle + "<br>");

// geometrizer program end

// The lifetime supply claculator start

document.write("<h1>The Lifetime Supply calculator</h1> <br>");
var favSnack = "Lays";
var currentAge = 15;
var maxAge = 65;
var perDayConsumeSnack = 3;
var totalEat = (maxAge - currentAge) * 3;
document.write("Your Favourite snack is " + favSnack + "<br>");
document.write("Current Age :" + currentAge + "<br>");
document.write("Maximum Age is " + maxAge + "<br>");
document.write("Amount Snacks per Day " + perDayConsumeSnack + "<br>");
document.write(
  "You will need " +
    totalEat +
    " Lays to last you until the ripe old age of " +
    maxAge +
    "."
);

// The lifetime supply claculator end

// chapter 6

// question 1 start

document.write("Result: <br>");
var a = 10;
document.write("The vale of a is " + a + " <br>");
document.write("...............................<br>");

document.write("The value of ++a :" + ++a + "<br>");
document.write("The value of a :" + a + "<br>");
document.write("The value of a++ :" + a++ + "<br>");
document.write("The value of a :" + a + "<br>");
document.write("The value of --a :" + --a + "<br>");
document.write("The value of a :" + a + "<br>");
document.write("The value of --a :" + a-- + "<br>");
document.write("The value of a :" + a + "<br>");

// question 1 end

// question 2 start

var a = 2;
var b = 1;
var result = --a - --b + ++b + b--;
// // --a is py a sy phy value decrease hogi phir print hogi mean --a = 1
// // --a - --b is main bhi pre decrement ho raha hai b main jisy a main howa tha tu ab --a=1 or --b=0
// // --a - --b + ++b is main perincreament ho raha hai mean phley increase hogi then print 1-0+2
// // --a - --b + ++b + b-- is main ab last b main postdecreament ho raha hai mean first print then decrease
// // 1-0+2+0=3
document.write("a is : " + a + "<br>");
document.write("b is : " + b + "<br>");
document.write("Result is : " + result);

// question 2 end

// question 3 start
var userName = prompt("what is your name", "write your name");
alert("Good Morning " + userName);

// question 3 end

// question 4 start

var userNum = Number(prompt("Write a Number"));
if (userNum !== 0) {
  document.write(userNum + " X 1 = " + userNum * 1 + " <br> ");
  document.write(userNum + " X 2 = " + userNum * 2 + " <br> ");
  document.write(userNum + " X 3 = " + userNum * 3 + " <br> ");
  document.write(userNum + " X 4 = " + userNum * 4 + " <br> ");
  document.write(userNum + " X 5 = " + userNum * 5 + " <br> ");
  document.write(userNum + " X 6 = " + userNum * 6 + " <br> ");
  document.write(userNum + " X 7 = " + userNum * 7 + " <br> ");
  document.write(userNum + " X 8 = " + userNum * 8 + " <br> ");
  document.write(userNum + " X 9 = " + userNum * 9 + " <br> ");
  document.write(userNum + " X 10 = " + userNum * 10 + " <br> ");
} else {
  document.write(5 + " X 1 = " + 5 * 1 + " <br> ");
  document.write(5 + " X 2 = " + 5 * 2 + " <br> ");
  document.write(5 + " X 3 = " + 5 * 3 + " <br> ");
  document.write(5 + " X 4 = " + 5 * 4 + " <br> ");
  document.write(5 + " X 5 = " + 5 * 5 + " <br> ");
  document.write(5 + " X 6 = " + 5 * 6 + " <br> ");
  document.write(5 + " X 7 = " + 5 * 7 + " <br> ");
  document.write(5 + " X 8 = " + 5 * 8 + " <br> ");
  document.write(5 + " X 9 = " + 5 * 9 + " <br> ");
  document.write(5 + " X 10 = " + 5 * 10 + " <br> ");
}

// question 4 end
