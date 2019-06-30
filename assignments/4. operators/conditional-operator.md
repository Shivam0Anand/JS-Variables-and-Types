## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

  ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    * [ ] Sub
    * [ ] Mul
    * [ ] Div

var a = Number(prompt("Enter No."));
var b = Number(prompt("Enter Second No."));
var operator = prompt("Enter add(+)/sub(-)/div(/)/mul(*)");

if(operator == "add" || operator == "+")
	alert(a+b);
else if(operator == "sub" || operator == "-"){
	if(a>=b){
		alert(a-b);
	}
	else{
		alert("Number Two is larger then Number one");
	}
}
else if(operator == "div" || operator == "/") {
	if(a>b)
		alert(a/b);
	else
		alert("Number Two is larger then Number one");
}
else if(operator == "mul" || operator == "*"){
	alert(a*b);
}


2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`
```js
var firstName = 'John';
var status = 'single';
// Your code goes here
if(status == 'single'){
  console.log("John is Single");
}
else
  console.log("John is married");
```

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
// your code goes here
var a= Number(prompt("Enter No."));
var b = Number(prompt("Enter other No."));
if(a>b)
	alert("larger no. is "+a);
else
  alert("larger no. is "+b);
```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
// Your code goes here
var a = Number(prompt("Enter No."));
var b = Number(prompt("Enter other No."));
var c = Number(prompt("Enter third No."));
var d = a*b*c;
if(d>0)
	alert("+ve");
else if(d<0)
    alert("-ve");
else
	alert("0");
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here
var a = +prompt("Enter Num");
switch(a){
case 1:
	alert("the no. is 1");
	break;
case 2:
	alert("the no. is 2");
	break;
case 3:
	alert("the no. is 3");
	break;
case 4:
	alert("the no. is 4");
	break;
case 5:
	alert("the no. is 5");
	break;
case 6:
	alert("the no. is 6");
	break;
case 7:
	alert("the no. is 7");
	break;
case 8:
	alert("the no. is 8");
	break;
case 9:
	alert("the no. is 9");
	break;
default:
	alert("try again");
}
```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// Your code goes here

let a = +prompt("Enter your marks");
switch(true) {
  case (a > 90):
    alert("Your grade is AA");
    break;
  case (a > 80 && a < 90):
    alert("Your grade is AB");
    break;
  case (a > 70 && a < 80):
    alert("Your grade is BB");
    break;
  case (a > 60 && a < 70):
    alert("Your grade is BC");
    break;
  case (a > 50 && a < 60):
    alert("Your grade is CC");
    break;
  case (a > 40 && a < 50):
    alert("Your grade is CD");
    break;
  case (a > 30 && a < 40):
    alert("Your grade is DD");
    break;
  case (a <= 30):
    alert("Your grade is FF")
    break;
}
```
