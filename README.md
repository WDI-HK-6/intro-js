# Introduction to JavaScript (JS)

# How are websites made?
- HTML defines static elements for the website 

# What if I want to modify these HTML elements?
- Understandable by web Browsers

# What is JavaScript?
- A dynamic computer programming language
- Most commonly for web pages on web browsers
- Most web pages are generated from HTML (HyperText Markup Language). 

# Fundamentals
We are going to learn fundamentals, before we will learn more advanced libraries like JQuery in the future

# JS Console
> The javascript prompt, aka “the Console”
> help
> 24
> 3.14

# Operators
### Addition (+)
1 + 1
### Substraction (-)
3 - 123
### Multiplication (*)
123 * 0.123
### Division (/)
123 / 2
## Special: Modulus (%)
123 % 2 = 1

### Order of Operations: PEMDAS
- recognize negative number as well
(5+7) * 3 = 12 * 3 = 36
(-3 * 4) + 3 - 12 / 2

# Comparators
### Greater than (>)
6 > 4 -> true
### Less Than (<)
9 < 5 -> false
### Equals (==)
3 == 4 -> false
### Not Equal (!=)
12 != 4 => true
### Greater than or equal to (>=)
8 >= -2 -> true
### Less than or equal to (<=)
10 <= 10 -> true

# Strings
- store and process ‘flat text’

### Quotation marks (beginning and ending a string)
- double quotation marks allows JS to recognize it as a string
> “Hello World!”
### Concatenate strings 
> “Hello” + “ “ + ”World!”
> “Hello World!”
### Concatenate numbers 
> “There are“ + 365 + “days in a year”
> “There are365days in a year”
> “There are 365 days in a year”
### Concatenate expressions
- expressions gets evaluated
> “Platform “ + 9 + “ and “ + 3/4
> “Platform 9 and 0.75”
> “Platform “ + 9 + “ and 3/4”
> “Platform 9 and 3/4”
### Some characters needs backslash notation in JS strings
\” -> “
\\ -> \
\t -> next tab
\n -> next line
Quoth the raven:
    "Nevermore!"
### String comparisons
“Harry” == “Harry” -> true
“Harry” == “you” -> false
“Harry” != “you” -> true
### Length of a string
“Harry”.length = 5
“Harry Chen”.length = 10 -> include all spaces and notations

# Variables
### Assignment
> var apples = 3
- variable keyword
- variable name
- assignment operator
- value to be stored

> apples -> 3

- no spaces in variable name
- no digit in front of variable name
- can have underscore
- can have number sign

### Using Camelcase
> var goodNameHere

- change variable content
> apples = 4
- no var keyword needed
> apples -> 4

> var oranges = 3
> var fruits = oranges + apples
> fruits -> 7
> fruits += 3 -> 10
> fruits = fruits * 2 => 20
> fruits *= 2 -> 40

### Concatenation
> “There are ” + apples + “ apples!”

### Incrementing / Decrementing
> apples ++
> oranges —— 

> var age = 10;
> var ageIn5Years  = age+5;

### Store strings in variables
> var platform = “Platform 9 and 3/4”
> platform.length
> var first = “asdfasfsafasdfsadf”
> var second = “asdfasfa3fsadnsdfgfsdasdfsd”
> first.length > second.length

### Finding specific characters within strings
- a number “index” starting from 0
> var myname = ‘Harry’
> myname[0]
> myname.charAt(0)
> myname.length
- ‘index’ will always be 1 less than the length since it starts at  0

### In practice
> var trainsOperational = 8
> var totalTrains = 12
> var operatingStatus = “ trains are operation today.”
> trainsOperation + “ out of “ + total Trains + operatingStatus
-> “8 out of 12 trains are operational today.”
-> you can change variable, and the string will be automatically updated

# JS File - running JS in an HTML File





# - write JS source files in HTML
