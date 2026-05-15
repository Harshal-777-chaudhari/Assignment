Core PhP :



Defination : PHP (Hypertext Preprocessor) is a widely used, open-source server-side scripting language specifically designed for web development.



PHP :

Hypertext Preprocessor



Version : 8.5.4



Composer : Dependency Manager for PHP Project

Composer is a tool for dependency management in PHP. It allows you to declare the libraries your project depends on and it will manage (intall/update) them for you.



PHP :

Core PHP



Object Oriented Programming :



SQL Programming :



Larvel :



M : Model : SQL Database



V : View : Ajax, Jquery, React Js



C : Controller : OOPS PHP



Query Builder :

Laravel's database query builder provides a convinent, fluent interface for creating and running database queries.



Eloquent Model :

Eloquent is the Object-Relational Mapper (ORM) included with the Laravel framework. It provides an expressive, ActiveRecord implementation for working with your database,



ORM :  Object Relational Mapper



&#x20;1. var\_dump()



&#x20;Sabse detailed output deta hai



Data type + value + length sab show karta hai

Deep debugging ke liye best



Example:



$x = "Hello";

var\_dump($x);



Output:



string(5) "Hello"



&#x20;2. print\_r()



Simple readable format deta hai



Sirf value show karta hai

Data type show nahi karta

Human-readable output



Example:



$x = "Hello";

print\_r($x);



Output:



Hello

&#x20;3. var\_export()



&#x20;PHP code jaisa output deta hai



Aisa output deta hai jo dobara PHP code mein use ho sakta hai

Mostly debugging + storing structure



Example:



$x = "Hello";

var\_export($x);



Output:



'Hello'



php :

variables :

normal variable : $variable\_name



$name = "Vraj";

$age = 20;



predefined functions :

echo : to display the data

print : to display the data



echo: Generally faster and can output multiple strings separated by commas.

print: Slightly slower, returns a value (1), and only accepts one argument.



Data Types :

String

Integer

Array : collection of data

Null

Decimal : float

Object

indexing :

forward indexing : 0, 1, 2, 3, 4,.....

1 Dimensional

2 Dimensional

Multidimensional



Assciate Array :



Array Methods and string Methods :

for print : print\_r, var\_dump, var\_export



ucfirst : a built-in function that converts the first character of a string to uppercase.

strtolower : convert all alphabetic characters in a given string to lowercase.

strtoupper :  convert all alphabetic characters in a string to uppercase.



Array Methods :

array\_unshift() : this will add the element at first index of array

array\_pop() : this will remove the element from last index of array

array\_splice() : this will remove the element from an array and, optionally replaces them with the new element

array\_splice() : syntax :array\_splice(array \&$input, int $offset, ?int $length = null, mixed $replacement = \[]): array

asort() : sort an associative array in ascending order according to the value

ksort() : sort an associative array in ascending order according to the key





Array Methods :



Function :

function setData()

{





}



Default function : non parametrized function



annoymous function



arrow function





Parametrized function :



function getData($para1, $para2, $para3){



}

getData($arg1, $arg2, $arg3){



}

getData($arg1, $arg2, $arg3);





Default parametrized function :



function myData($name = "Siddhesh", $age = 21, Salary = 65000){





}



myData();





Annoymous funtion :



$result = function($x, $y, $z){



};



function calling :



$result(21, 15, 16);



$result();



Arrow funtion :



$calculate = fn($x, $y) => $x, $y;



function calling :



$calculate(25, 25);



implode() : is a built-in function used to join array elements into a single string. It is often described as the "glue" that binds an array together.



explode() : is a built-in function used to split a string into an array of substrings based on a specified delimiter.

&#x20;It is commonly used for tasks like parsing CSV data, splitting URLs, or breaking sentences into individual words.



Foreach loop :  a specialized control structure designed specifically for iterating over arrays and objects.

ForEach kab use  hota hai ?

Jab hume array ke sab elements access karne ho

foreach sirf array aur object ke liye use hota hai



For loop : is used when you know in advance how many times a script should run.

It is a compact control structure that groups initialization, condition checking, and incrementing into a single line



Neon Number : is a number where the sum of the digits of its square is equal to the original number. There are only three known neon numbers in base 10: 0, 1, and 9.



Armstrong Number : a positive integer where the sum of its individual digits, each raised to the power of the total number of digits, is equal to the number itself.



Fibonacci Number : a mathematical series where each number is the sum of the two preceding ones.



Palidrome Number : an integer that remains unchanged when its digits are reversed.



Database connectivity :



mysqli method :



pdo method : PHP Data Object



Session : A session is a server-side storage mechanism that keeps track of user data during a single visit to a website



Cookie : A cookie is a small text file (maximum 4KB) that the web server stores on the client's computer.



isset() : The isset() function determines if a variable is declared and is not NULL.



unset() : The unset() function is used to destroy a specified variable, effectively making it undefined.



include: Generates a warning (E\_WARNING) if the file is missing. The script will continue to execute the remaining code.



require: Generates a fatal error (E\_COMPILE\_ERROR) if the file is missing. The script will stop execution immediately.



include\_once: Checks if the file has already been included. If it has, the statement is ignored; otherwise, it behaves like include.



require\_once: Ensures the file is only required once, avoiding errors like function or class redeclarations.



Global variables :



$\_GET /$\_POST : used to collect data from HTML forms and URL parameter.



$\_SESSION : stores data across multiple pages for a specific user.



$\_SERVER : contains information about headers, paths, and script location.



$\_FILES : handle file uploads to the script.



$\_COOKIE : accesses data sent by the browser via HTTP cookies.



&#x20;











&#x20;

