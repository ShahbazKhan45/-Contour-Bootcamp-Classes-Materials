# -Contour-Bootcamp-Classes-Materials

<h3>Second Class</h3>
<h1>Bootstrap</h1>
<p>Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development.
    <br>
    It contains HTML, CSS and JavaScript-based design templates for typography, forms, buttons, navigation, <br>
    and other interface components.
</p>

<h2>How to Link Bootstrap</h2>
<h5>Method 1: Using the Bootstrap Content Delivery Network (CDN) <br> For CSS</h5>
<p>Copy this stylesheet link to the <head> tag of your desired HTML file. <br>
    #For CSS
    <h6>
        <link rel=stylesheet” href=”https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css”rel=”nofollow”
            integrity=”sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm” crossorigin=”anonymous”>
    </h6>

        #For JS
        <p>Copy this stylesheet before the end of the <body> tag of your desired HTML file. <br>
                <script src=”https://code.jquery.com/jquery-3.2.1.slim.min.js”
                    integrity=”sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN”
                    crossorigin=”anonymous”></script>

                <script src=https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js
                    integrity=”sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q”
                    crossorigin=”anonymous”></script>

                <script src=”https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js”
                    integrity=”sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl”
                    crossorigin=”anonymous”></script>
        </p>

        You can easily use the bootstrap through its class example is mentioned below:
        <div class="container">
            <div class="row">
                <div class="col-md-12">Good Luck :)</div>
            </div>
        </div>
</p>



<h2>Containers</h2>
<p>Containers are the most basic layout element in Bootstrap and are required when using our default grid system. <br>
    Containers are used to <strong> contain, pad, and (sometimes) center the content </strong> within them. <br>
    The w3-container class is the perfect class to use for all HTML container elements like: <br>
    <!-- <div>, <article>, <section>, <header>, <footer>, <form>, and more -->
</p>

<h2>Break Points</h2>                        
<p>CSS breakpoints are points where the website content responds according to the device width, <br> 
    allowing you to show the best possible layout to the user. CSS breakpoints are also called <br> 
    media query breakpoints, as they are used with media query</p>
                       
<h2>Components</h2>
<p>Over a dozen reusable components built to provide iconography, dropdowns, input groups, navigation, alerts, and much more.</p>

<h2>Buttons</h2>                        
<p>Use Bootstrap's custom button styles for actions in forms, dialogs, and more with support for multiple sizes, states, and more.</p>

<hr>

<h1>Programming Fundamentals</h1>
<p>Programming involves activities such as analysis, developing understanding, generating algorithms, verification of requirements of algorithms</p>

<h2>Datatypes</h2>
<p>In Javascript, there are five basic, or primitive, types of data. <br> 
    The five most basic types of data are:</p>
<ul>
    <li>Strings     ==> var a="Shahbaz Khan";</li>
    <li>Numbers     ==> let b = 7;</li>
    <li>Booleans    ==> let c = true;</li>
    <li>Undefined   ==> var d;</li>
    <li>Null <strong>In JavaScript null is "nothing". It is supposed to be something that doesn't exist. <br> 
        Unfortunately, in JavaScript, the data type of null is an object.</strong> <br>
         ==> let person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
         person = null;</li>
    <li>Object      ==> let person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};</li>
</ul>
<h2>Arrays</h2>
<p>In JavaScript, the array is a single variable that is used to store different elements. <br> 
    It is often used when we want to store a list of elements and access them by a single variable.
<br>
// Initializing while declaring
var house = ["1BHK", "2BHK", "3BHK", "4BHK"];
</p>

<h2>Loop</h2>
<p>Loops are used in JavaScript <strong> to perform repeated tasks based on a condition.</strong> <br> 
    Conditions typically return true or false . A loop will continue running until <br> 
    the defined condition returns false <br>

    for (initialization; condition; finalExpression) {
        // code
      }
//example
      for (let i = 0; i < 9; i++) {
        console.log(i);
      }
      
      // Output:
      // 0
      // 1
      // 2
      // 3
      // 4
      // 5
      // 6
      // 7
      // 8
</p>

<h2>Function</h2>
<p>A function is a block of code that performs a specific task <br>

    function hello(){
        console.log("Hello!");
    }

    hello()

</p>
                        
<h2>Conditions</h2>
<p>Conditions are <strong> statements that are created by the programmer <br> 
    which evaluates actions in the program and evaluates if it's true or false. </strong><br> 
    If-then-else statement allows conditional execution based on the evaluation of an expression</p>

<hr>

<h1>JavaScript</h1>

<h2>Arrow</h2>
<p>Arrow function is one of the features introduced in the ES6 version of JavaScript. <br> 
It <strong> allows you to create functions in a cleaner way compared to regular functions. </strong><br>
For example, This function 

<br>

/* function expression*/ <br>
let x = function(x, y) { return x * y; }
</p>

<h2>Clousure</h2>
<p>A clousure function is an inner function that has access to the outer (enclosing) function's variable. <br>
    function outerFun(){
        var text1 = "This is outer text of variable";

        function innerFun(){
            var text2 = `This is inner Text of the variable and ${text1}`;
            console.log(text2)
        }
        innerFun()
    }
    outerFun();
</p>

<h2>Recursion</h2>
<p>Recursion is a process of calling itself. A function that calls itself is called a recursive function. <br> 
    The syntax for recursive function is: <br>
    // program to find the factorial of a number
function factorial(x) {

    // if number is 0
    if (x === 0) {
        return 1;
    }

    // if number is positive
    else {
        return x * factorial(x - 1);
    }
}

const num = 3;

// calling factorial() if num is non-negative
if (num > 0) {
    let result = factorial(num);
    console.log(`The factorial of ${num} is ${result}`);
}    
</p>
