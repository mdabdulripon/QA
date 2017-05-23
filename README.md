## GENERAL:

### STAND FOR:
     -> HTML: Hypertext Markup Language
     -> CSS: Cascading Style Sheet
     -> XML: Extensible Markup Language
     -> AJAX: Asynchronous Javascript And Xml
     -> JSON: JavaScript Object Notation
     -> HTTP: Hypertext Transfer Protocol
     -> XHTML: Extensible Hypertext Markup Language
     -> SGML: STANDARD GENERALIZED MARKUP LANGUAGE
     -> DTD: Document Type Definition
     -> DOM: Document Object Model
     -> API: Application Program Interface
     -> REST: REpresentational State Transfer
     -> W3C: World Wide Web Consortium

### How do you speed up your site!
     ->To speed up the site performance we need to do:
          01. Minimize HTTP Requests
          02. Reduce server response time
          03. Enable browser caching
          04. Optimize CSS File
          05. Reduce the number of plugins you use on your site
          06. Reduce image size
          07. Load JavaScript asynchronously
          08. Code your site for mobile-first quality and speed
          09. Cache as much as possible

### What is Vanilla javascript!
     -> Vanilla Js is a name to refer to using plain JavaScript without any additional libraries like jQuery.

### what is Asynchronous method!
     -> Asynchronous means that the script will send a request to the server, and continue it's execution without
     waiting for the reply. As soon as reply is received a browser event is fired.

### What is web worker!
     -> Web worker is a JavaScript that runs in the background independently of other scripts, without affecting the
     performance of the page. You can continue to do whatever you want while the web worker runs in the background.

### What is MVC!
     -> MVC stands for Model View Controllers. It is a software design pattern for web development application.
          a. Model is responsible for maintaining data.
          b. View is responsible for displaying data.
          c. Controller is integrate data between Model and View.

### What is DOM!
     -> The DOM is stands for Document Object Model. It’s a W3C standard, which defines a standard for accessing Documents.
     W3C separated DOM in three ways:
           a. Core DOM (For All Documents.)
           b. XML DOM ( For XML)
           c. HTML DOM ( For HTML )



## ANGULAR:

### What's New in Angular 4!
     -> Smaller & Faster Apps:
          It is quite a bit faster and smaller than angular 2.
     -> View Engine Size Reduce:
          Improved the compilation time. These changes reduce around 60% size in most cases.
     -> Animation Package:
          Animations now have their own package @angular/platform-browser/animations
     -> NgIf with Else:
          Now possible to use an else syntax.

###  Advantages for Angular2
     01. Angular2 has better performance.
     02. Angular2 has more powerful template system.
     03. Angular2 provide simpler APIs, lazy loading and easier to application debugging.
     04. Angular2 much more testable

### What is Components!
     -> Component decorator allows you to mark a class as an Angular component and provide additional
     metadata that determines how the component should be processed, instantiated and used at runtime.
     -> Angular components are a subset of directives.
     -> A component must belong to an NgModule in order for it to be usable by another component or application.

### What is Directive!
     -> There are three kinds of directives in Angular:
          01. Components directives
          02. Structural directives
               -> Structural Directives change the structure of the view. Two examples are NgFor and NgIf.
          03. Attribute directives
               -> Attribute directives are used as attributes of elements. NgClass, NgStyle, NgModel
               are Attribute directives.
### What is Pipes!
     -> Pipes transform displayed values within a template.
     -> Angular comes with some Built  in pipes. Such as: DatePipe, UpperCasePipe, LowerCasePipe,
     CurrencyPipe, and PercentPipe.

### What is Router!
     -> Router enables navigation from one view to the next as users perform application tasks.





## JAVASCRIPT

### What are the data type in javascript!
     - Number
     - String
     - Boolean
     - Function
     - Objects
     - Null
     - Undefined

### What are the comparison operator!
     - == [ Double Equals ]
     - === [ Triple Equals ]
     - != [ Not Equal ]
     - > [ Greater than ]
     - < [ Less than ]
     - >= [ Greater than equal ]
     - <= [ Less Than equal ]

### What are the logical operator!
     - && [ And ]
     - ||[ Or]
     - ! [ Nor ]

### Undeclared Variable:
     Undeclared variables are not exist in program, when program tries to run there will be a runtime error.
### Undefined Variables:
     Undefined variables are declared in program but have not given any value. If programs tries to run an undefined
     value is returned.
### Global Variable:
     Global Variables are declared outside of the function and can be reusable throughout the application.
### Local Variable:
     Local variables are declared inside the function and can not be access for other function.

### What is the differences between = , == , and ===!
     -> Single equal is an assignment operator.
     -> Double equals is a comparison operator. Also known as a loose equality operator. For example, it execute
     the number which is string in other side.
     -> Triple equals is also a comparison operator. Also known as a strict equality operator. For example, for
     execute it has be be same in both side.

### What is an Array and How do you create an array!
     -> Arrays are used to store multiple values or elements in a single variable.
     Example: Declared a variable name
     Var a = [ and assign the value inside the square brackets separated by comma ]

     -> Array method are in the below:
          - join(): Join all array into a string.
          - toString(): Convert an array to a string separated by comma.
          - pop(): Remove the last element of an array
          - push(): Add new element at the end of an array.
          - shift(): Remove the first element of an array.
          - unshift(): Add new elements at the first of an array.
          - sort(): Arrange the elements in alphabetical order.
          - reverse(): Reverse the elements in an array.
          - concat(): Create new elements by connecting two arrays.


### what is an Object and how do you create an object!
     -> An object is a collection of properties, and a property is associates between a name (or key) and a value.
     Example: Declared a variable name:
     var person = {
          first_name:"Abdul",
          last_name:"Ripon",
          age : 24,
          eye_color: "blue"
     };
     Note: [ The person is an object and first_name, last_name, age and eye_color it’s property ]

### What is an anonymous function?
     -> A function without name is called an Anonymous Function.
     Example:
     var x = function (a, b){
          return a * b
     };
     document.getElementById("demo").innerHTML = x (4, 3);

### What is Closures!
     -> Closures are functions that refer to independent variables. I mean, variables that are used locally, but
     defined in an enclosing scope.
          var add = (function () {
    	          var counter = 0;
	          return function () {
                    return counter += 1;
               }
          })();
          function myFunction(){
              	document.getElementById("demo").innerHTML = add();
          }

     -> The variable add is assigned the return value of a self-invoking function.
     -> The self-invoking function only runs once. It sets the counter to zero, and returns a function expression.
     -> This is called a JavaScript closure. It makes it possible for a function to have "private" variables.
