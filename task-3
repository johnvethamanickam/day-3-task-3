**1.How to compare two JSON have the same properties without order**  
```js  
let obj = {name : "person 1", age : 5};  
let obj1 = {age : 5, name : "person 1"};  
  
function isEqual(obj, obj1){  
  
  var objkeys = Object.keys(obj);  
  var obj1keys = Object.keys(obj1);  
      
    if (objkeys.length != obj1keys.length) {  
        return false;  
    }  
    for (var objkey of objkeys) {  
        if (obj[objkey] != obj1[objkey]) {  
            return false;  
        }  
    }  
    return true;  
}  
console.log(isEqual(obj, obj1));  
```  
** **  
  
**2.Use the rest countries API URL-->[https://restcountries.com/v3.1/all](https://restcountries.com/v3.1/all) and display all the      countries flag in the console.**  
```js  
var xhr = new XMLHttpRequest();  
  
xhr.open('GET', '[https://restcountries.com/v3.1/all'](https://restcountries.com/v3.1/all'));  
xhr.responseType = 'json';  
xhr.send();  
  
xhr.onload = function(){  
    var resObj = xhr.response;  
    for(var i = 0; i<resObj.length; i++){  
        //console.log(resObj[i].length);  
        console.log(resObj[i].flag);  
    }  
}  
```  
** **  
  
**3.Use the same rest countries and print all the countries *names*, *regions*, *sub-region* and *population*.**  
```js  
//countries names  
var xhr = new XMLHttpRequest();  
  
xhr.open('GET', '[https://restcountries.com/v3.1/all'](https://restcountries.com/v3.1/all'));  
xhr.responseType = 'json';  
xhr.send();  
  
xhr.onload = function(){  
    var resObj = xhr.response;  
    for(var i = 0; i<resObj.length; i++){  
        console.log(resObj[i].name);  
    }  
}  
  
//countries region  
var xhr = new XMLHttpRequest();  
  
xhr.open('GET', '[https://restcountries.com/v3.1/all'](https://restcountries.com/v3.1/all'));  
xhr.responseType = 'json';  
xhr.send();  
  
xhr.onload = function(){  
    var resObj = xhr.response;  
    for(var i = 0; i<resObj.length; i++){  
        console.log(resObj[i].region);  
    }  
}  
  
//countries sub-region  
var xhr = new XMLHttpRequest();  
  
xhr.open('GET', '[https://restcountries.com/v3.1/all'](https://restcountries.com/v3.1/all'));  
xhr.responseType = 'json';  
xhr.send();  
  
xhr.onload = function(){  
    var resObj = xhr.response;  
    for(var i = 0; i<resObj.length; i++){  
        console.log(resObj[i].subregion);  
    }  
}  
  
//countries population  
var xhr = new XMLHttpRequest();  
  
xhr.open('GET', '[https://restcountries.com/v3.1/all'](https://restcountries.com/v3.1/all'));  
xhr.responseType = 'json';  
xhr.send();  
  
xhr.onload = function(){  
    var resObj = xhr.response;  
    for(var i = 0; i<resObj.length; i++){  
        console.log(resObj[i].name.common);  
        console.log(resObj[i].population);  
    }  
}
```
 
**Question 4**
**task 1**
 
**1.Declare four variables without assigning values and print them in console**  
```js  
var a;  
var b;  
var c;  
var d;  
  
console.log(a);  
console.log(b);  
console.log(c);  
console.log(d);  
```  
  
**2. How to get value of the variable myvar as output**  
```js  
var myvar= 1;  
console.log(myvar);  
```  
  
**3. Declare variables to store your first name, last name, marital status, country and age in multiple lines**  
```js  
var firstName = "John";  
var lastName ="Vethamanickam";  
var maritalStatus = "Unmarried";  
var country = "India";  
var age = 25;  
  
console.log("My Firstname is "+ firstName);  
console.log("My Lastname is "+ lastName);  
console.log("My MaritalStatus is "+ maritalStatus);  
console.log("My country is "+ country);  
console.log("My age is "+ age);  
```  
  
**4. Declare variables to store your first name, last name, marital status, country and age in a single line**  
```js  
var firstName = "John", lastName ="Vethamanickam", maritalStatus = "Unmarried", country = "India", age = 25;  
```  
  
**5.Declare variables and assign string, boolean, undefined and null data types**  
```js  
var myName = "john";  
var age = 25;  
var married = false;  
  
console.log("My Name is "+ myName);  
console.log("I am "+ age+ " years old");  
console.log(unmarried);  
  
var a=null;  
var b;  
  
console.log(a);  
console.log(b);  
```  
  
**6.Convert the string to integer  
i)parseInt**  
```js  
var a=parseInt("10");  
var b=parseInt("20");  
  
console.log(a);  
console.log(b);  
console.log(parseInt("10.80"));  
console.log(parseInt("10.00"));  
console.log(parseInt("10.33")) ;  
console.log(parseInt("34 45 66"));  
console.log(parseInt("   60   "));  
console.log(parseInt("40 years"));  
console.log(parseInt("He was 40"));  
console.log(parseInt("10", 10));  
console.log(parseInt("010"));  
console.log(parseInt("10", 8));  
console.log(parseInt("0x10"));  
console.log(parseInt("10", 16));  
```  
**ii)Number**  
```js  
console.log(Number(true)); //For booleans, Number() returns 0 or 1.  
console.log(Number(false));  
  
// console.log(Number(new Date())); //For dates, Number() returns milliseconds since January 1, 1970 00:00:00  
  
console.log(Number("999 888"));  
console.log(Number([9,9]));  
console.log(Number([9.9]));  
```  
**iii)plus sign(+)**  
```js  
const x = "10";  
let y;  
y = +x;//It converts a string into a number.  
  
console.log(y);  
console.log(typeof y);  
console.log(+'');  
console.log(+'hello');  
```  
  
**7.Write 6 statement which provide truthy & falsey values**  
    *undefined ,  
     null ,  
     NaN ,  
     0 ,  
     "" (empty string), and  
     false*
     
**task 2**
**1.square of a number**
 
```js
var a = 2;
var sq = a * a;
console.log(sq);
```
 
**2.swapping of two numbers**
 
 
```js
var a = 10;
var b = 20;
[a,b] = [b, a];
console.log(a);
```
 
**3,.addition of two numbers**
 
```js
var a = 5;
var b = 3;
var c = 8;
var sum = a + b + c;
console.log(sum);
```
 
**4. celcius to fahrenheit conversion**
 
```js
var cel = 64;
var far = (cel * 1.8) + 32;
console.log(cel + " " + "degree celcius is equal to" +" "+ far+ " "+ "degree fahrenheit");
```
 
**5. Meter to miles**
   1 meter = 0.000621371 miles
 
```js
function convertMetersToMiles(meters) {
    const miles = meters * 0.000621371;
    return miles;
  }
  const meters = 400;
  const miles = convertMetersToMiles(meters);
  console.log(meters + " " + "meters is equal to" +" "+ miles + " " + "miles");
```
 
**6. Pounds to kg**
   1 pound  = 0.453592 kilograms
 
```js
function convertPoundsToKilograms(pounds) {
    const kilograms = pounds * 0.453592;
    return kilograms;
  }
  const pounds = 150;
const kilograms = convertPoundsToKilograms(pounds);
console.log(pounds + " " + "pounds is equals to"+" " +kilograms+" "+ " kilogram");
```
 
**7. claculate batting average**
 
```js
function calculateBattingAverage(runs, dismissals) {
    const average = runs / dismissals;
    return average.toFixed(2); // Return the average rounded to 2 decimal places
  }
  const runs = 345;
const dismissals = 15;
const battingAverage = calculateBattingAverage(runs, dismissals);
console.log(battingAverage); // Output: 23.00
```
 
**8.Calculate five test scores and print their average**
 
```js
var s1 = 88;
var s2 = 89;
var s3 = 96;
var s4 = 92;
var s5 = 98;
var sum = s1+s2+s3+s4+s5;
var average = sum/5;
console.log(`The average of 5 test score is ${average}`);
```
 
**9.Power of any number x ^ y**
 
```js
var x = 5;
var y = 3;
console.log(Math.pow(x, y));
```
 
**10.Calculate Simple Interest**
 
```js
var p = 3000;
var n = 1;
var r = 7;
var sI = (p*n*r)/100;
console.log(`The Simple Interest is ${sI}`);
```
 
**11.Calculate area of an equilateral triangle**
 
```js
var a=20;
var area = (1.73*a*a)/4;
console.log(`The area of equilateral triangle is ${area}`);
```
 
**12.Area Of Isosceles Triangle**
 
```js
var base = 10;
var height = 20;
var area = (base*height)/2;
console.log(`The area of isosceles triangle is ${area}`);
```
 
**13.Volume of Sphere**
 
```js
var radius = 5;
volume = (4/3) * Math.PI * Math.pow(radius, 3);
volume = volume.toFixed(4);
console.log(`The volume of sphere is ${volume}`);
```
 
**14.Volume Of Prism**
 
```js
var l = 18;
var b = 12;
var h = 9;
volume = (l * b * h) / 2;
console.log(`The volume of triangular prism is ${volume}`);
```
 
**15.Area of triangle**
 
```js
var l = 10;
var b = 12;
var area = (l*b)/2;
console.log(`The area of triangle is ${area}`);
```
 
**16.Give the Actual cost and Sold cost, Calculate Discount Of Product**
 
```js
var actual = 100;
var sold = 50;
var discount =((actual-sold)*100)/actual;
console.log(`Discount of a product is ${discount}%`);
 
```
 
**17.Given their radius of a circle and find its diameter, circumference and area.**
 
```js
var r = 5;
var diameter = 2 * r;
var circumference = 2 * Math.PI * r;
circumference = circumference.toFixed(3);
var area = Math.PI * r * r;
area = area.toFixed(4);
console.log(`The diameter of circle is ${diameter}`);
console.log(`The circumference of circle is ${circumference}`);
console.log(`The area of circle is ${area}`);
```
 
**18.Given two numbers and perform all arithmetic operations**
 
```js
//Addition
var a=10;
var b=2;
var x=a+b;
console.log(`Addition of ${a} and ${b} is ${x}`);
 
//subtraction
var y=a-b;
console.log(`subtraction of ${b} from ${a} is ${y}`);
 
//Multiply
var z =a*b;
console.log(`Multiply of ${a} and ${b} is ${z}`);
 
//Division
var d=a/b;
console.log(`Division of ${a} by ${b} is ${d}`);
 
//Modulus
var m = a%b;
console.log(`Remainder is ${y}`);
 
//Exponentiation
console.log(a**b);//a ** b produces the same result as Math.pow(a,b)
```
 
**19.Display the asterisk pattern as shown below(No loop needed):
 
```js
var str = "*****\n*****\n*****\n*****\n*****";
console.log(str);
```
 
**20.Calculate electricity bill? For example, a consumer consumes 100 watts per hour daily for one month. Calculate the total energy bill of that consumer if per unit rate is 10?**
 
```js
var p=0.1;
var t=1;
var e=p*t;
var emonth=30*e;
var cost=10;
var bill=cost*emonth;
console.log(`Total electricity bill per month is Rs.${bill}`);
```
 
**21.Calculate CGPA**
 
 
```js
var percentage=70;
var cgpa = percentage/9.5;
cgpa=cgpa.toFixed(1);
console.log(`${cgpa}CGPA`);
```
 
** **
**task 3**
 
**1.  Write a loop that makes seven calls to `console.log` to output the following triangle:**
 
```js
let output = '';
for (let i = 1; i <= 7; i++) {
  output += '#';
  console.log(output);
}
```
 
 
**2. write a code to count the elements in the array . Don’t use length property**
 
```js
function countElements(arr) {
    let count = 0;
    for (let i = 0; myarr[i] !== undefined; i++) {
      count++;
    }
    return count;
  }
  const myarr = [11, 22, 33, 44, 55];
  const count = countElements(myarr);
  console.log(count); // Output: 5
```
 
**Arrays:**
**1. var myarray=[11,22,33,44,55]
write a code to count the elements in the array . Don’t use length property
 
Declare an empty array;
 
 
```js
var myarray = [11,22,33,44,55];
var count = 0;
for (var i in myarray) {
count++;
}
console.log(count);
```
 
**2.Foods variable holds the names of your top 20 favorite foods, starting with the best food. How can you find your fifth favorite food?
 
let foods=[]
 
Find the length of your foods array
 
```js
let food = ["Fish Curry", "Fish Fry", "Chicken65", "Mutton Chukka", "Briyani", "Dhosa", "Chappathi", "Poori", "Parotta", "Naan", "Idly", "Paneer", "Gopi65", "Maggie", "Sambar", "Dry Fish", "Aviyal", "Rasam", "Idiyappam", "Appam"]  
  
console.log(food.length);  
  
//find your fifth favorite food  
console.log(food[4]);
```
 
**3Starting from the existing friends variable below, change the element that is currently “Mari” to “Munnabai”.
 
let friends = [  
“Mari”,  
“MaryJane”,  
“CaptianAmerica”,  
“Munnabai”,  
“Jeff”,  
“AAK chandran”  
];
 
function dataHandling(input){  
for (var i = 0; i < input.length; i++) {  
  
}  
}
 
dataHandling(friends);.
 
```js
let friends = ["Mari","MaryJane","CaptianAmerica","Munnabai","Jeff","AAK chandran"];
function dataHandling(input){
    var index = input.indexOf("Mari");
    input[index] = "Munnabai";
    console.log(input);
}
dataHandling(friends);
```
 
**4. tarting from the friends variable below, Loop and Print the names till you meet CaptianAmerica.
 
const friends = [  
“Mari”,  
“MaryJane”,  
“CaptianAmerica”,  
“Munnabai”,  
“Jeff”,  
“AAK chandran”  
];
 
function dataHandling(input){  
for (var i = 0; i < input.length; i++) {  
  
}  
}
 
dataHandling(friends);
 
```js
let friends = ["Mari","MaryJane","CaptianAmerica","Munnabai","Jeff","AAK chandran"];
function dataHandling(input){
for (var i = 0; i < input.length; i++){
    console.log(input[i]);
    if(input[i] === "CaptianAmerica"){
        break;
    }
    
}
}
dataHandling(friends);
```
 
**5. Find the person is ur friend or not.
 
const friends = [  
“Mari”,  
“MaryJane”,  
“CaptianAmerica”,  
“Munnabai”,  
“Jeff”,  
“AAK chandran”  
];
 
function dataHandling(input, name){  
for (var i = 0; i < input.length; i++) {  
  
}  
}
 
let found = dataHandling(friends,”Jeff”);
 
console.log(found);
 
```js
let friends = ["Mari","MaryJane","CaptianAmerica","Munnabai","Jeff","AAK chandran"];
function dataHandling(input, fr){
    for(var i = 0; i< input.length;i++){
        if(input[i] === fr){
            return true;
        }
    }
    return false;
}
let found = dataHandling(friends, "Mari");
console.log(found);
```
 
**6.We have two lists of friends below. Use array methods to combine them into one alphabetically-sorted list.
 
var friends1 = [  
“Mari”,  
“MaryJane”,  
“CaptianAmerica”,  
“Munnabai”,  
“Jeff”,  
“AAK chandran”  
];
 
var friends2 = [  
“Gabbar”,  
“Rajinikanth”,  
“Mass”,  
“Spiderman”,  
“Jeff”,  
“ET”  
];
 
function dataHandling(input){  
//Your code goes here  
}
 
dataHandling(friends);
 
```js
let friends1 = ["Mari","MaryJane","CaptianAmerica","Munnabai","Jeff","AAK chandran"];
var friends2 = ["Gabbar","Rajinikanth","Mass",
"Spiderman","Jeff","ET"];
function dataHandling(input){
    var combine = input[0].concat(input[1]);
    combine.sort();
    return combine;
}
var sortedFriends = dataHandling([friends1,friends2]);
console.log(sortedFriends);
```
 
 
 
**1.Get the first item, the middle item and the last item of the array**  
 
```js  
let friends = ["Mari", "MaryJane", "CaptianAmerica", "Munnabai", "Jeff", "AAK chandran"];  
//first item  
console.log(friends[0]);  
  
//last item  
last = friends.length - 1;  
console.log(friends[last]);  
  
//middle item  
var middle = friends[Math.floor(friends.length / 2)];  
console.log(middle);  
```  
 
**2. Add your name to the end of the friends array, and add another name to beginning.**  
 
```js  
let friends = ["Mari", "MaryJane", "CaptianAmerica", "Munnabai", "Jeff", "AAK chandran"];  
//add at end  
friends.push("Nivetha");  
console.log(friends);  
  
//add at beginning  
friends.unshift("Balaji");  
console.log(friends);  
```  
 
**3.Add Mr or Ms to the names in the friends array.**  
 
```js  
let friends = ["Mari", "MaryJane", "CaptianAmerica", "Munnabai", "Jeff", "AAK chandran"];  
  
const modify =friends.map(name=>`Mr.${name}`);  
  
console.log(friends);  
console.log(modify);  
```  
 
**4. Concat all the names the friends array and return as comma “,” seperated string.**  
 
```js  
let friends = ["Mari", "MaryJane", "CaptianAmerica", "Munnabai", "Jeff", "AAK chandran"];  
let j=friends.join();  
  
console.log(j);  
```  
 
**5. Find the friends names who has letter ‘a’ and return the list.**  
 
```js  
let friends = ["Mari", "MaryJane", "CaptianAmerica", "Munnabai", "Jeff", "AAK chandran"];  
  
for(var i = 0; i < friends.length; i++)  
{  
    if(friends[i].indexOf('a') != -1)  
    {  
        console.log(friends[i]);  
    }  
}  
```  
 
**6.Find the avg length of all the friends names. Get the individual length of the names and do the avg.**  
 
```js  
let friends = ["Mari", "MaryJane", "CaptianAmerica", "Munnabai", "Jeff", "AAK chandran"];  
  
avg = friends.join('').length / friends.length;  
  
console.log(avg);  
```  
 
**7. Find the names and return the list starting with letter M.**  
 
```js  
let friends = ["Mari", "MaryJane", "CaptianAmerica", "Munnabai", "Jeff", "AAK chandran"];  
  
for(var i = 0; i < friends.length; i++)  
{  
    if(friends[i].startsWith("M") == true)  
    {  
        console.log(friends[i]);  
    }  
}  
```  
 
**8. Find the name with max characters and return the name.**  
 
```js  
let friends = ["Mari", "MaryJane", "CaptianAmerica", "Munnabai", "Jeff", "AAK chandran"];  
  
var lgth = 0;  
var longest;  
  
for (var i = 0; i < friends.length; i++) {  
  if (friends[i].length > lgth) {  
    var lgth = friends[i].length;  
    longest = friends[i];  
  }  
}  
```  
 
**9. Find the name with min characters and return the name.**  
 
```js  
let friends = ["Mari", "MaryJane", "CaptianAmerica", "Munnabai", "Jeff", "AAK chandran"];  
  
console.log(  
    friends.reduce((a, b) => a.length <= b.length ? a : b)  
  )  
```
 
**1. Find the average in the array below.  
Make sure you add only the numbers and do avg.
 
const friendsInfo = [6, 12, ‘Mari’, 1, true, ‘Munnabai’, ‘200’, ‘CaptianAmerica’, 8, 10];
 
```js
const friendsInfo = [6, 12, "Mari", 1, true, "Munnabai", "200", "CaptianAmerica", 8, 10];
const numbers =friendsInfo.filter(value => typeof value === number);
let sum = numbers.reduce((a, b) => a + b);
let res = sum/numbers.length;
console.log(res);
```
 
**2. Print the contents of the input variable
 
var input = [  
[“0001”, “Roman Alamsyah”, “Bandar Lampung”, “21/05/1989”, “Membaca”],  
[“0002”, “Dika Sembiring”, “Medan”, “10/10/1992”, “Bermain Gitar”],  
[“0003”, “Winona”, “Ambon”, “25/12/1965”, “Memasak”],  
[“0004”, “Bintang Senjaya”, “Martapura”, “6/4/1970”, “Berkebun”]  
]
 
function dataHandling(input){  
for (var i = 0; i < input.length; i++) {  
//Your code goes here
 
}  
}
 
dataHandling(input);
 
```js
var input = [
["0001", "Roman Alamsyah", "Bandar Lampung", "21/05/1989", "Membaca"],
["0002", "Dika Sembiring", "Medan", "10/10/1992", "Bermain Gitar"],
["0003", "Winona", "Ambon", "25/12/1965", "Memasak"],
["0004", "Bintang Senjaya", "Martapura", "6/4/1970", "Berkebun"]
]
 
function dataHandling(input){
for (var i = 0; i < input.length; i++) {
    var x = input[i];
    var roll = x[0];
    var name = x[1];
    var city = x[2];
    var dob = x[3];
    var hobby = x[4];
    console.log("Roll NO : " + roll)
    console.log("Name : " + name)
    console.log("City : " + city)
    console.log("DOB : " + " "+ dob)
    console.log("Hobby : " + hobby)
    console.log();
}
}
 
dataHandling(input);
```
 
**3.Add a new key value pair to myobject  
key : ten  
value : ten
 
```js
myobject = {1:"one","11":1,"name":"arun"}
myobject["ten"] = "ten";
console.log(myobject);
```
 
**4. Write out an object literal to represent the data below.
 
Guvi, Geek, 6, IIT-M RP,Chennai.
 
```js
var addr= {
    Name : "guvi, geek",
    location : "6, IIT-M RP,Chennai"
};
console.log(addr);
```
 
**5. How would you represent the following data using a combination of object literals and arrays? (You can describe a strategy without typing or writing out the whole thing.)
 
Guvi, Geek, 6, IIT-M RP,Chennai.  
Amazon, Inc, 31, SP Infocity, Chennai.  
Google, Alphabet, 34 Amphitheater Parkway, MountainView.  
Tesla, Inc , 32, 333 Santana Row,San Jose.
 
```js
var addr=[{
    Name : "guvi, geek",
    location : "6, IIT-M RP,Chennai"
},
{
    Name : "Amazon, Inc",
    location : "31, SP Infocity, Chennai."
},
{
    Name : "Google, Alphabet",
    location : "34 Amphitheater Parkway, MountainView."
 
},
{
     Name : "Tesla, Inc ",
    location : "32, 333 Santana Row,San Jose."
}
];
console.log(addr);
```
