# Javascript
JavaScript Documentation

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

Reference : [javascript.info](https://javascript.info/)

