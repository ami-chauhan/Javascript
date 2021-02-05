# Javascript
JavaScript Documentation <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" width="100" height="100"> 



* *JavaScript (JS)* , is a programming language that conforms to the ECMAScript specification. JavaScript is high-level, just-in-time compiled, and multi-paradigm. It has curly-bracket syntax, dynamic typing, prototype-based object-orientation, and first-class functions.

* JavaScript is used both on the client-side and server-side that allows us to make web pages interactive.

> print statement in javascript

    console.log(' hii ');

> for informing effect of desicion on web-page (pop-up)
    
    alert(' hii ');
> javascript in html 
    
    <script>  javascript code </script>

### Type conversions:
string | numeric | boolean
-------|---------|--------
let value = true; alert(typeof value); | console.log(2+9); console.log("2"+"9"); | alert( Boolean(1) ); alert( Boolean(0) );
boolean | 11   29 | True   False

### Basic Operators:

#### terms: 
* unary( single variable and operator (x = -x))
* binary ( two variables and one operator (x+y))
* operand (variables (a,b,c,x))

##### mathematical: + , - , * , / , % , **
example exponential 2 ** 2 = 4 and 4 ** (1/2) = 2

##### string concatenation using binary + 
+ treats and thing betwwen '' single quotes as string 
    
    console.log('2'+77); 
    277
    
##### numeric conversion using unary +


    let a = "2";
    let b = "3";
    console.log( a + b);    23 //concates
   
    console.log( +a + +b );   5 //adds
##### Increment Decrement operators:
    a=3
    a++;// 3 assigns and increments
    b=5
    ++b;// 6 increments and assigns

##### bitwise operators: 
operator | symbol
---------|-------
AND |  & 
OR | | 
XOR | ^ 
NOT | ~ 
LEFT SHIFT | << 
RIGHT SHIFT | >> 
ZERO-FILL RIGHT SHIFT | >>> 

### Data Type
1. String
let name = "vaibhavi" 
2. Number
let n = 1111 
3. Boolean
true or false
4. Array
let cars = ["i-10", "Audi", "BMW"] 
5. Object
let person = {firstName: "Shilpa", lastName: "Solanki"} 
6. Undefined
let car;   A variable without a value
7. Null
value which represents “nothing”, “empty” or “value unknown”

References : 
[javascript.info](https://javascript.info/)
[w3schools](https://www.w3schools.com/)
