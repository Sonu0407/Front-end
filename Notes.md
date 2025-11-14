HTML5
CSS
JS
Bootstrap
ReactJS

Hyper text markup language 

HTML4 vs HTML5

CSS
cascading style sheets
1. Inline CSS
2. Internal CSS
3. External CSS

JS
JavaScript

we write a script to make our web page functionable

we can also use Typescript to make our web page functionable(TS is a advanced than JS)

                                 (Server)
Front - end---------API----------Backend-----------------Database
                    (REDIS)
                    (REDIS KEY)










Header
Aside
Section
Banner
template
footer

HTML 4 was dividing sections in terms of div 
there was not header, footer, etc..

HTML 5 was introduced header section, footer and section

SEO
Search Engine Optimization

1. page :
title
description
keywords
url

2. Page Schema

3. BreadCrumbs means home/library/data

clockwise: top, right, bottom, left
ex: margin: 0,   0 ,    0,     0

in case of two
it is only top and bottom, left and right
ex: margin: 0 , 0
            TB  LR

align item means it makes the element horizontal center or which side you need
justify content means it makes the element vertically center or which side you need

html list
1. ordered list -- ol
2. un-ordered list -- ul

justify-content: space-between means it divides the space between the block like 50-50

class.
id #
tag </>

Form

Table

Table Heading 

Table data(body)

Cookies

webstorage

1. local storage

2. session storage

Bootstrap (RWD)

Responsive web designs

Netlify -> 100gb free storage (server)

Git code commit

push = upload
pop = Delete
pull = download

1. Git Init
To initialize into project with repository

2. Git Add
To add files to the staging area

3. Git commit 
To commit files to the repository

4. Git Push
To commit files to the repository

5. Git Pull
To pull files from the remote repository

6. Git Branch
To check current branch

7. Git remote -v
To check remote repository

8. Git status
To check status of the repository

9. Git stash
To check status of the repository

10. Git stash pop
To pop stash changes

data types in js
1. primitive
2. non-primitive

primitive data types
1. string
2. Number
3. boolean
4. undefined
5. Null
6. Symbol

non-primitive data types
1. object: key-value pairs. {}
2. array: Indexed collections. []
3. function: reuseable block of code. ()

variables

let = local scoped
var = global scoped
const = constant

hositing
a variable can be called before declaration, it called as hositing, to avoid hositing use use the strict mode(use strict) in script.

Operators = 

1. Arithmetic Opeartors used for mathematical calculations.\

operator | Description            | example              | result
1. +        Addition
2. -        subtraction
3. *        Multiplication
4. /        Division
5. %        Modules (remainder)
7. **       Exponentiation
8. ++       Increment
9. --       Decrement

increment
1. pre increment
2. post increment

2. Assignment Operator = Used to assign values to variables.

Operator
1. =
2. +=
3. 

3. Comparsion Operator = Used to compare two values

a. (==)    Equal to
b. (===)   strict equal
c. ===     type+value
d. !=      Not equal
e. !==     strict not equal
f. >       grater than
g. <       less than
h. >=      Greater than or equal
i. <=      less than or equal

4. logical operators = used for logical operations.

a. &&      logical AND. true && false -> false
b. ||      logical OR.  a || b
c. !       logical NOT. !true -> false

5. String Operators = used to manipulate strings.

a. +       string Concatenation     "Hello" + "World"               o/p = "Hello World"
b. +=      Concatenation assign     let x = "Hi "; x += "Adil";     o/p = "Hi Adil"

array methods
1. push -- End of array works on copy of array
2. pop --- End of array works on copy of array
3. shift -- start of array works on same array
4. unshift -- start of array works on same array
5. slice -- any index of array works on same array
6. splice -- any index of array works on same array

const
const keyword then variable name and values 
example: const city = "Mumbai"

this refers to the object that is currently calling the function
this points to that object itself
can use it anywhere in javascript

for test in javascript
if (!/[a-z]/.test(PASSWORD)) use this test method
output returns true if password contains a to z but only lowercase

1. Understanding cookies :

cookies are small pieces of data stored in browser. they help websites remeber information about users, like login status, preference, or shopping cart items.

stored as name = value pairs.
Usefull for tracking small data across sessions.

2. how we write a cookie :
document.cookie = "username=JohnDoe; expires = Fri, 31 Dec 2024 23:59:59 GMT; path = /";

3. how we read a cookie :
console.log(document.cookie);
// output: "username=JohnDoe"

4. Deleting Cookies :
To delete a cookie, set its expiration date to the past:
document.cookie = "username=; expires=Thu, 01 Jan 1970 00:00:00 UTC; path=/";

5. Counting with cookies :
it say you want to count how maany times the user visited the page.

count = "1...n"
string concat + count +
template literal `${count}` as f-string in python

Call Back functions :

1. map()
The map() method is used to loop through an array and create a new array with the result of applying a function
to each element.

2. setTimeout()
The setTimeout() method runs a function once after a specified delay (in milliseconds).

3. setInterval()
The setInterval() method runs a function repeatedly, at a fixed time interval (in milliseconds), untill stopped.

eg:

let nums = [1, 2, 3];
let doubled = nums.map(num => num * 2);
console.log(doubled); // Output: [2, 4, 6]

(num => num * 2)

num = 1 * 2 (0)
num = 2 * 2 (1)
num = 3 * 2 (2)

1. create a function to double the give array [1, 2, 3]

2. Use map() to convert all strings in an array  to uppercase? 

3. Use map() to get only the names from this array of objects:

4. Add a prefix to every item in an array using map()?

Async/Await
javascript async and await;
1. to create responsive applications in javascript
2. to execute concurrent process
3. no block state or no need to wait till function ends.
4. async and await are used in javascript to work with asynchronous operations more easily 
5. they allow code to wait for long tasks (like fetching data) without stopping the entire program.

async -> Marks a function that may run tasks which take time(but returns promise(1/0)).
await -> Pauses the function untill the function(promise) finishes, but does not block other code.
Used for -> API calls, database operations, file reading, timers, etc.
Benefit -> Code becomes easier to read and understand (looks like normal step-by-step code)

Real-life Example

Example: ordering food in a Restaurant

1. You order biryani (this takes time to prepare)

2. But you don't stand in the kitchen waiting (that would block everything).

3. Instead, you sit and talk with friends (other work continues).

4. When the biryani is ready, the waiter delivers it (result comes later).

This is async behavior:

https://jsonplaceholder.typicode.com/posts/1

https://jsonplaceholder.typicode.com/posts


1. Order placed = Request sent

2. Waiter prepares silently = Awaiting result

3. You keep doing other things = Non-blocking

4. Food delivered = function(promise) resolved

return new Promise((resolve => {}(rejected => {})));

javascript promise

1. it is a special javascript object
2. it will return either resolved or rejected status 
3. it always returns response, it wont break during transaction/process
4. reject and resolve both are callback function it will execute either anyone
5. we access promise by method :
then ()
catch ()

React Notes

React Js
1. it is a javascript libarary
2. React js is used to create ui components
3. virtual DOM support
4. its very fast and performance
5. single page application(SPA) development
6. component based architectire
7. server side rendering




setup


1. navigate to project folder/directory
cmd : cd foldername


2. how to create react setup
cmd: npm install create-react-app


3. how to create react project
cmd: npx create-react-app reactproject
note: project name should be in small letters


4. run/execute react project
cmd: npm start




Component Syntax


1. Create a js file,
2. create a funciton
3. Return the function
4. export the function
5. import the function in app.js/index.js
6. render(call) the function in app.js/index.js


function Demo() {
 return (
   <div>
     <h1>This is Demo Function from demo.js file</h1>
   </div>
 );
}
export default Demo();

working react
1. npm start
2. Index.html
3. Index.js
4. App.js
  a. Contact_page   {Routing} to app.js
  b. About_page
  c. Services_page
  d. products_page


function in react
1. function/component
2. component defination
3. component calling(exporting) (to reuse this same component we must import the exported 
component to the file we are expecting to use it)

3. import css files

React routing 

to implement single page application
to navigate one page to another page using routing

React Routing Component
1. BrowserRouter -> to handle browser navigation action
2. Routes -> Routes will have route Configuration
3. Route -> Route Path to be rendered Component based on ink url text
4. Link -> to link to the path

To setup react routing need to install routing package

npm install react-router-dom

Flow of routes
Link => To

To => path

Routes => Route

Route => path,component

index.js => BrowserRoutes



