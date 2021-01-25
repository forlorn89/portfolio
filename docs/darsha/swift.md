
- [Hello World](#hello-world)
- [Variable](#variable)
- [Declare a Variable](#declare-a-variable)
- [comments](#comments)
- [Arithmetic Operators](#arithmetic-operators)
- [Compound Assignment Operators](#compound-assignment-operators)
- [Type](#type)
- [String Interpolation](#string-interpolation)
- [Constants](#constants)
- [Conditionals](#conditionals)
- [If Statement](#if-statement)
- [Else Statement](#else-statement)
- [Comparison Operators](#comparison-operators)
- [Else If Statements](#else-if-statements)
- [Ternary Conditional Operato](#ternary-conditional-operato)
- [Switch Statement](#switch-statement)
- [Switch Statement: Interval Matching](#switch-statement-interval-matching)
- [Switch Statement: Compound Cases](#switch-statement-compound-cases)
- [Switch Statement: where Clause](#switch-statement-where-clause)
- [Introduction to Logical Operators](#introduction-to-logical-operators)
- [Logical AND Operator](#logical-and-operator)
- [Logical OR Operator](#logical-or-operator)
- [Logical NOT Operator](#logical-not-operator)
- [Combining Logical Operators](#combining-logical-operators)
- [Controlling Order of Execution](#controlling-order-of-execution)
- [Loops](#loops)
- [The for-in Loop](#the-for-in-loop)
- [The stride() Function](#the-stride-function)
- [Iterating Through Strings](#iterating-through-strings)
- [Using Underscore](#using-underscore)
- [The continue Keyword](#the-continue-keyword)
- [The break Keyword](#the-break-keyword)
- [While Loop](#while-loop)
- [challenge](#challenge)
- [Introduction to Arrays](#introduction-to-arrays)
- [Creating an Array Literal](#creating-an-array-literal)
- [Index](#index)
- [.count Property](#count-property)
- [.append() Method](#append-method)
- [.insert() and .remove() Methods](#insert-and-remove-methods)
- [Iterating Over an Array](#iterating-over-an-array)
- [Introduction to Sets](#introduction-to-sets)
- [Creating a Set](#creating-a-set)
- [.count and .isEmpty](#count-and-isempty)
- [Inserting Elements](#inserting-elements)
- [Removing Elements](#removing-elements)
- [Checking For Elements](#checking-for-elements)
- [Iterating Through a Set](#iterating-through-a-set)
- [Set Operations: .intersection()](#set-operations-intersection)
- [Set Operations: .union()](#set-operations-union)
- [Set Operations: .symmetricDifference()](#set-operations-symmetricdifference)
- [Set Operations: .subtracting()](#set-operations-subtracting)
- [Dictionaries](#dictionaries)
- [Creating a Dictionary Literal](#creating-a-dictionary-literal)
- [Type Inference](#type-inference)
- [Adding Elements](#adding-elements)
- [Updating Elements](#updating-elements)
- [Removing Elements](#removing-elements-1)
- [Inspecting a Dictionary](#inspecting-a-dictionary)
- [Accessing Values](#accessing-values)
- [Iterating through a Dictionary](#iterating-through-a-dictionary)
- [Using .keys and .values](#using-keys-and-values)
- [Functions](#functions)
- [Calling a Function](#calling-a-function)
- [Returning a Value](#returning-a-value)
- [Parameters and Arguments](#parameters-and-arguments)
- [Multiple Parameters](#multiple-parameters)
- [Omitting Argument Labels](#omitting-argument-labels)
- [Returning Multiple Values](#returning-multiple-values)
- [Implicit Return](#implicit-return)
- [Default Parameters](#default-parameters)
- [Variadic Parameters](#variadic-parameters)
- [In-Out Parameters](#in-out-parameters)
- [summary of Function](#summary-of-function)
- [Creating a Structure](#creating-a-structure)
- [Default Property Values](#default-property-values)
- [Creating an Instance](#creating-an-instance)
- [Accessing and Editing Properties](#accessing-and-editing-properties)
- [The Init Method](#the-init-method)
- [Memberwise Initialization](#memberwise-initialization)
- [Structure Methods](#structure-methods)

------


## Hello World
* print("Hello, world!") this is how we print in Swift

## Variable
* A variable is simply a name that represents a particular piece of your computer’s memory that has been set aside for you to store, retrieve, and use data.
  * Int: integer numbers
  * Double: floating-point numbers
  * String: a sequence of characters
  * Bool: true/false values

## Declare a Variable
  * var score = 0
  * var is a keyword used to declare variables.
  * score is the name of the variable.
  * = is the assignment operator.
  * 0 is the value of the variable.
  * this is how we print our variable print(score)

## comments
  * A single line comment will comment out a single line and is denoted by two forward slashes // 
example: // Prints "hi"
print("hi")
  * A multiline comment will comment out multiple lines and is denoted by /* to begin the comment, and */ to end the comment:
example: /* This is all commented out.
print("hi")
None of this is going to run! */

## Arithmetic Operators
  * + addition
  * - subtraction
  * * multiplication
  * / division
  * % modulo (divides and gives the remainder)
for example:
  var score = 0
  // score is 0
 
  score = 4 + 2
  // it is now 6
 
  score = score - 2
  // it is now 4
 
  score = 4 * 2
  // it is now 8
 
  score = 4 / 2
  // and now 2
 
  score = 5 % 2
  // and now 1

## Compound Assignment Operators
* var age = 99
* age = age + 1
* print(age)  // Prints 100

--
short version will be:
* var age = 99
* age += 1
* print(age)  // Prints 100

--
Here are some different compound assignment operators we can use:

* += add and assign the sum.
* -= subtract and assign the difference.
* *= multiply and assign the product.
* /= divide and assign the quotient.
* %= divide and assign the remainder.

## Type
* var artist: String
* artist = "Daniel Johnston"
* var artist: String = "Daniel Johnston"

## String Interpolation

* In Swift, to insert a value into a string using string interpolation, we can write the value in parentheses, and write a backslash \ before the parentheses.
* var albums = 17
* print("Daniel Johnston made \(albums) studio albums.")
* Daniel Johnston made 17 studio albums.

## Constants
  * for Constant we can not reassigned the variable 

  * Once we assign a value to a constant in Swift, it becomes immutable. This means that the value stored in it cannot be changed.

## Conditionals

## If Statement

  *The if keyword is followed by a condition whose value must be true or false.
  *The condition is immediately followed by a code block.
  *A code block is a snippet of code enclosed in a pair of curly braces, { }.
  *The code block is executed only when the condition is true.
  *If the condition is false, the code block does not run.
example:
  * var isLoggedIn = true
 
  *if isLoggedIn {
  print("Welcome back!")
}

## Else Statement

  * An else statement must be used in conjunction with an if statement and cannot stand on its own.
  * An else statement does not accept a condition and is immediately followed by a code block.

## Comparison Operators

  * Swift supports the following comparison operators:
  * == Equal to
  * != Not Equal to
  * > Greater than
  * < Less than
  * >= Greater than or equal to
  * <= Less than or equal to

## Else If Statements


*Swift provides us with a tool called the else if statement which allows us to add additional conditions to a standard if/else statement.

## Ternary Conditional Operato

* A ? B :C
* A is the condition to check for
* B is the expression to use if the condition is true
* C is the expression to use if the condition is false
for example:
var orderSuccessfullyPlaced = false 
 
if orderSuccessfullyPlaced {
  print("Your order was received.")
} else {
  print("Something went wrong.")
}
we can rewrite it like this:
orderSuccessfullyPlaced ? print("Your order was received.") : print("Something went wrong.")

## Switch Statement
 var city = "Rome"
 
if city == "Rapa Nui" { 
  print("Moai 🗿")
} else if city == "New York" {
  print("Statue of Liberty 🗽")
} else if city == "Rome" {
  print("Colosseum 🏛")
} else {
  print("A famous landmark is the Eiffel Tower!")
}

we can rewrite it like this:

switch city {
  case "Rapa Nui":
    print("Moai 🗿")
  case "New York":  
    print("Statue of Liberty 🗽")
  case "Rome":
    print("Colosseum 🏛")
  default: 
    print("A famous landmark is the Eiffel Tower!")
}

## Switch Statement: Interval Matching

* In Swift, a range is indicated by three consecutive dots, ..., also known as the closed range operator

var year = 1943
 
switch year {
  case 1701...1800:
    print("18th century") 
  case 1801...1900:
    print("19th century")
  case 1901...2000: 
    print("20th century")
  case 2001...2100: 
    print("21st century")
  default: 
    print("You're a time traveler!")
}

## Switch Statement: Compound Cases

* its use of multiple values in a single case. These are known as compound cases. 

var country = "India"
 
switch country {
  case "USA", "Mexico", "Canada":
    print("\(country) is in North America. 🌏")
  case "South Africa", "Nigeria", "Kenya":
    print("\(country) is in Africa. 🌍")
  case "Bangladesh", "China", "India":
    print("\(country) is in Asia. 🌏")
  default: 
    print("This country is somewhere in the world!")
}

## Switch Statement: where Clause

var randomNumber = Int.random(in: 0...10)
 
switch randomNumber {
  case let x where x % 2 == 0:
    print("\(randomNumber) is even")
  case let x where x % 2 == 1:
    print("\(randomNumber) is odd")
  default:
    print("Invalid")
}

## Introduction to Logical Operators

* && (AND)
* || (OR)
* ! (NOT)

## Logical AND Operator

* The logical, &&, operator evaluates two operands and returns a Boolean result. It returns true only when both operands are true and returns false when at least one operand is false.

* && is denoted by two ampersand symbols and translates to AND.

for example:

var time = 8 // PM 
var phoneInUse = true 
var brightness: Double
 
if time >= 8 && phoneInUse {
  brightness = 0.75 
} else {
  brightness = 1 
}
 
print(brightness)

## Logical OR Operator

* || is denoted by two pipe symbols and translates to OR.

for example:

var snowing = false 
var raining = true
 
if snowing || raining {
 print("Wear waterproof shoes!")
}

## Logical NOT Operator

* The logical, ! is NOT

let a = true
let b = false

print(!a) // Prints: false 
print(!b) // Prints: true 
print(!(true && false)) // Prints: true 

## Combining Logical Operators

let weekday = true 
let dayOff = false 
let weekend = false
 
if weekday && dayOff || weekend {
  print("Do something fun!") 
} else {
  print("Get some work done") 
}
// Prints: Get some work done

## Controlling Order of Execution

* true || true && false && true 
* use of parentheses also makes our code easier to read and interpret.
* (true || true) && (false && true)

## Loops

* In programming, this entire process with a starting condition, repetition, and ending condition is called a loop

## The for-in Loop

* We use for-in loops to iterate over a sequence of values, such as Strings (which is a sequence of characters) or ranges (sequence of numbers)

for example:

print("Why is 6 afraid of 7? Because …")
for num in 7...9 {
  print(num)
}

## The stride() Function

for num in stride(from: 0, to: 6, by: 2) {
  print(num)
}

* The first argument, from: 0 is the starting number of the sequence (0).
* The second argument, to: 6 is the end of the sequence (6). But notice, we didn’t print out 6 which means this end number is not included.
* The third argument, by: 2 determines how much to increment (or decrement if we use a negative number) during each iteration.

## Iterating Through Strings

* Let’s say we wanted to look over a string and see if it contains "z". In a program, that means we would loop through the characters of a String. In each iteration would we check if the character was a "z".

for example:

var quote = "our whole life is solving puzzles."
 
for character in quote {
  print(character)
  if character == "z" {
    print("There's a z!")
  }
}

## Using Underscore

for num in 1...10 {
  print("I will not write smelly code.")
}

* We’ve seen these errors before when we wrote our loop but didn’t add any code inside its body. Therefore, to avoid the warning (i.e. code smell), it’s good practice to replace num with an underscore _:

for _ in 1...10 {
  print("I will not write smelly code.")
}

## The continue Keyword

let challenge = "bring it"
 
for char in challenge {
  switch char {
    case "a", "e", "i", "o", "u":
      continue
    default:
      print(char)
  }
}

## The break Keyword

* We can use the break keyword to exit out of the loop before the loop fully completes:

let respect = 556
 
for pageNum in 1...1000 {
  if pageNum == respect {
    print("Respect means: to admire someone for their abilities.")
    break
  }
  print("On page \(pageNum) and still no 'respect'!")
}

## While Loop

* when we’re not exactly sure how long we need to loop for.

* This loop allows us to continue iterating for as long as a condition remains true.

var total = 0
 
while total < 50 {
  let diceRoll = Int.random(in: 1...6)
  total += diceRoll
}

## challenge 


* If you want to challenge yourself:

* Create a loop that iterates from 1 to 100 that prints out whether the current number in the iteration is even or odd.
Use a loop to determine if a number is a prime number.
Loop through a string and count how many characters are in it.
Recreate the follow pattern using loops:

*
**
***
****

## Introduction to Arrays

* An array stores an ordered collection of values
* To create an empty array of a certain type, we can use the initializer syntax:

var name = [Type]()

var scores = [Int]()

## Creating an Array Literal

var location = [40.7245, -73.9979]

var location: [Double] = [40.7245, -73.9979]

## Index

* An index refers to an item’s position within an ordered list. Arrays in Swift are zero-indexed, meaning the first item has index 0, the second index 1, and so on.

* var vowels = ["a", "e", "i", "o", "u"]
* The item at index 0 is "a".
* The item at index 1 is "e".
* The item at index 2 is "i".
* The item at index 3 is "o".
* The item at index 4 is "u".

## .count Property

var grocery = ["🥓", "🥞", "🍪", "🥛", "🍊"]

* When we print out grocery.count:

print(grocery.count)
The output will look like this:

5

## .append() Method

* We can add a new item to the end of an array by calling the array’s .append() method:

var gymBadges = ["Boulder", "Cascade"]
We can add a new item, "Thunder", to the end of the array by:

gymBadges.append("Thunder") 
 
// ["Boulder", "Cascade", "Thunder"]

* Alternatively, append an array of one or more items with the addition assignment operator +=:

gymBadges += ["Thunder", "Rainbow"]
 
// ["Boulder", "Cascade", "Thunder", "Rainbow"]

## .insert() and .remove() Methods

* To insert an item in the array at a specified index, we can call the .insert() method.

var moon = ["🌖", "🌗", "🌘", "🌑"]

moon.insert("🌕", at: 0)
 
// ["🌕", "🌖", "🌗", "🌘", "🌑"]

* The .insert() method takes two values:

The value to be inserted.
The at: and the index of the insertion.
So the code above inserted "🌕" at index 0.

* To remove an item from the array, call the array’s .remove() method:

moon.remove(at: 4)
 
// ["🌕", "🌖", "🌗", "🌘"]
The .remove() method only takes in one value, at: and the index of removal.

So the code above removed "🌑" at index 4

## Iterating Over an Array

* What happens if we want to iterate through items of an array? We can use a for-in loop!

* For example, suppose we have a String array that looks like this:

var employees = ["Michael", "Dwight", "Jim", "Pam", "Andy"]

We can write a for-in loop like so:

for item in employees {
  print(item)
}

## Introduction to Sets

* A set is an unordered collection of unique elements.
* Set elements cannot be repeated, while that is allowed in arrays.
* A set does not have a defined order, while an array does.

## Creating a Set

* The syntax for creating an empty set looks like this:

var setName = Set<Type>()

var setName: Set = [Value1, Value2, Value3]

* We must use the Set keyword.
* All values must be contained within brackets [] and each value is separated by a comma ,.
* There are no repeated values.
* The elements of the set must all be the same type.

## .count and .isEmpty

setName.isEmpty

* If there are no values in the set, the expression will return true.
* If there are values, the expression will return false

var instruments = Set<String>()
 
if instruments.isEmpty {
  print("Let's sign up for piano lessons!")
}
// Prints: Let's sign up for piano lessons!

var lunchbox: Set = ["Apple", "Sandwich"]

* Then, we could use .count to find out how many items we have in lunchbox:

print("I have \(lunchbox.count) items in my lunchbox!")
 
// Prints: I have 2 items in my lunchbox!

## Inserting Elements

* We can use .insert() to add elements to a set using this syntax:

setName.insert(NewValue)
plantShelf.insert("Graptopetalum")

## Removing Elements

* If we need to remove an element from a set, we can use .remove().

plantShelf.remove("Haworthia")

* If we wanted to remove every single element from a set, we could use the .removeAll() method:

setName.removeAll()
plantShelf.removeAll()

## Checking For Elements

* If we want to check whether or not an element exists within a set, we can use the .contains() method.

* We can use the following syntax to check for an element inside of a set:

setName.contains(Value)

* We can use the following if/else statement with foodAtHome.contains("Salsa") as our conditional:

if foodAtHome.contains("Salsa") {
  print("We don't need any more salsa.")
} else {
  print("Let's buy more salsa.")
}
 
// Prints: Let's buy more salsa.

## Iterating Through a Set

* To iterate over every item of a set, we can use this syntax:

for Value in setName {
  // Body of loop
}

var chocoChipCookies: Set = ["Flour", "Chocolate Chips", "Butter", "Eggs", "Sugar", "Baking Powder"]

* We can use a for-in loop that will print() all the ingredients we need:

for ingredient in chocoChipCookies {
  print(ingredient)
}

## Set Operations: .intersection()

* We can use the .intersection() method to find matching values in two different sets:

var newSet = SetA.intersection(SetB)

var northHemisphere: Set = ["South America", "Europe", "North America", "Africa", "Asia"]
 
var southHemisphere: Set = ["Australia", "Antarctica", "Africa", "South America", "Asia"]

* We can use .intersection() to create a set called bothHemispheres that contains continents that exist in both hemispheres:

var bothHemispheres = northHemisphere.intersection(southHemisphere)

## Set Operations: .union()

* Another set operation we can use is .union(). This operation creates a set by combining the values of two sets together.

The syntax for creating a set using .union() is:

var NewSet = SetA.union(SetB)

var book1: Set = ["Pig 1", "Pig 2", "Pig 3", "Wolf"]
 
var book2: Set = ["Little Red Riding Hood", "Grandma", "Wolf"]

* We can use .union() to combine all the characters into one set called fairyTales:

var fairyTales = book1.union(book2)

* Imagine finding a third book, book3:

var book3: Set = ["Jack", "Blunderbore", "Beanstock"]

* With set operations, we can combine multiple sets like this:

var fairyTales = book1.union(book2).union(book3)

## Set Operations: .symmetricDifference()

* The .symmetricDifference() operation can be used to find elements that exist in one of the given sets, but not both.

* The syntax for creating a set using .symmetricDifference() looks like this:

var NewSet = SetA.symmetricDifference(SetB)

var nintendoSwitch: Set = ["Animal Crossing", "DOOM Eternal", "Stardew Valley"]
 
var playStation4: Set = ["DOOM Eternal", "Stardew Valley", "The Last of Us"]

var exclusiveGames = nintendoSwitch.symmetricDifference(playStation4)

["Animal Crossing", "The Last of Us"]

## Set Operations: .subtracting()

* This method creates a new set of elements by removing the overlapping data of one set from another set.

To use .subtracting() in our program, we can use this code:

var newSet = SetA.subtracting(SetB)

var animals: Set = ["Bison", "Mountain Gorilla", "Hedgehog", "Sea Turtle", "Vaquita", "Ocelet"]
 
var notEndangered: Set = ["Bison", "Hedgehog", "Ocelet"]

var endangered = animals.subtracting(notEndangered)

["Vaquita", "Mountain Gorilla", "Sea Turtle"]

## Dictionaries

* A dictionary is an unordered collection of paired data

* empty dictionary would be like:

var dictionaryName: [KeyType: ValueType] = [:]

* We need to declare the data type of the keys and the values.
After the assignment operator =, we use [:] to declare its an empty dictionary.

We can also create an empty dictionary using initializer syntax:

var dictionaryName = [KeyType: ValueType]()

We declare the key and value type after the assignment operator.

We add parentheses () after declaring the data types.

Empty dictionary literal syntax:

var yearlyPopulation: [Int: Int] = [:]

Initializer syntax:

var yearlyPopulation = [Int: Int]()

## Creating a Dictionary Literal

* The syntax to create a populated dictionary looks like this:

var dictionaryName: [KeyType: ValueType] = [
  Key1: Value1,
  Key2: Value2,
  Key3: Value3
]

var fruitStand: [String: Int] = [
  "Apples": 12,
  "Bananas": 20
]

## Type Inference

* When we first learned how to declare a dictionary, our code looked like this:

var fruitStand: [String: Int] = [
  "Apples": 12,
  "Bananas": 20
]

* With type inference, we can initialize fruitStand with this syntax:

var fruitStand = [
  "Apples": 12,
  "Bananas": 20
]

## Adding Elements

* Let’s say we created a dictionary donutPrices:

var donutPrices = [
  "Strawberry": 2,
  "Chocolate": 3
]

* We could add a third element to donutPrices using the following code:

donutPrices["Boston Cream"] = 4

## Updating Elements

var musicGenre = [
  "Duke Ellington": "Jazz",
  "Taylor Swift": "Country",
  "David Bowie": "Rock"
]

* If we wanted to update the value associated with the key "Taylor Swift" using subscript syntax, our code would look like this:

musicGenre["Taylor Swift"] = "Pop"

* We also have the option of changing our values using the .updateValue() method:

musicGenre.updateValue("Pop", forKey: "Taylor Swift")

## Removing Elements

* In Swift, the keyword nil describes something as being empty or having no value

var bookShelf = [
  "Goodnight Moon": "Margaret Wise Brown",
  "The BFG": "Roald Dahl",
  "Falling Up": "Shel Silverstein"
]

bookShelf["The BFG"] = nil 

or

bookShelf.removeValue(forKey: "The BFG")

or

bookShelf.removeAll()

## Inspecting a Dictionary

dictionaryName.isEmpty

* If the dictionary is empty, the expression will return true.
* If there are elements in the dictionary, the expression will return false.

*This property will return an integer that represents the number of elements contained within a dictionary:

dictionaryName.count

## Accessing Values

var fruitNames = [
  "mango": "Mangifera indica",
  "banana": "Musa paradisicum",
  "apple": "Pyrus malus"
]

var appleScientific = fruitNames["apple"]

if let appleScientific = fruitNames["apple"] {
  print(appleScientific)
} else {
  print("This key does not exist.")
}

## Iterating through a Dictionary

* Having more two or more values wrapped in parentheses () and separated by commas , is called a tuple.

var classGrades = [
  "Raymond": 100,
  "Rosa": 82,
  "Jake": 73,
  "Terry": 90
]
 
for (name, grade) in classGrades {
  print("\(name) has a grade of \(grade)")
}

## Using .keys and .values

* The .keys property stores a collection of dictionary keys,  * The .values property stores a collection of dictionary values.

var fruitStand = [
  "Apples": 12,
  "Bananas": 20,
  "Oranges": 18
]
print(fruitStand.keys)

["Bananas", "Oranges", "Apples"]

* If we printed fruitStand.values, our output would include these values:

[20, 18, 12]

##  Functions

* Swift functions are chunks of reusable code that achieve a certain outcome

Here’s the set up:

func functionName() -> returnType {
 // function's task goes here
} 

* Following the functionName is a pair of ( ) that can hold optional input values known as parameters.

1: func functionName() { where the -> and type are omitted entirely.

2: func functionName() -> Void { where Void is listed as the type and not return anything.

* Lastly, the returnType is followed by a code block that holds the code for the function’s task.

## Calling a Function

* To call a function in Swift, type out its name followed by parentheses ().

* Take the following makeSushiRoll()

## Returning a Value

* Passing a value from a function allows us to use it in other functions or save it in a variable until the need for it arises

let birthYear = 1994
var currentYear = 2020
 
func findAge() -> Int {
  return currentYear - birthYear
}
 print(findAge()) // Prints: 26

or

var age = findAge()
 
print(age) // Prints: 26

## Parameters and Arguments

* If a parameter exists, an argument must be passed in when the function is called. Otherwise, the compiler will throw an error.

* The argument must be the same type of value that the parameter is declared to have.

* When referencing a function, include the parameter name(s) in its title followed by a colon such as findGardenArea(side:).

func findGardenArea(side: Int) -> Int {
  return side * side
} 

var area = findGardenArea(side: 5) 
print(area) // Prints: 25

## Multiple Parameters

func didQualify(slowestDriver: Bool, retired: Bool) -> String {
 
  if slowestDriver || retired {
    return "Eliminated"
  } else {
    return "Qualified"
  }
}

print(didQualify(slowestDriver: true, retired: false)) 

## Omitting Argument Labels

let adults = 2
let students = 15 

func museumEntry(_ numAdults: Int,_ numStudents: Int) -> Int {
  var studentTicket = 14
  var adultTicket = 25
  var total = (studentTicket * numStudents) + (adultTicket * numAdults)
  return total

}
print(museumEntry(adults, students))

## Returning Multiple Values


func favoriteCuisine() -> (name: String, dish: String) {
 return (name: "Russian", dish: "Pelmeni") 
}

let cuisine = favoriteCuisine()

print("My favorite \(cuisine.name) dish is \(cuisine.dish)!")

## Implicit Return

func findRemainder(dividend: Int, divisor: Int) -> Int {
   dividend % divisor
}
print(findRemainder(dividend: 10, divisor: 4))

## Default Parameters

func bookingTicket(passengerName: String = "Sogol", seatClass: String = "Economy", timeOfDeparture: Int) -> String {

  return "\(passengerName), your seat class is \(seatClass), and you will be departing at \(timeOfDeparture)."
  
}

print(bookingTicket(timeOfDeparture: 9))

print(bookingTicket(seatClass: "Business", timeOfDeparture: 9))

## Variadic Parameters

func avgSongLength(times: Int...) -> Int {
  var total = 0
  for time in times {
    total += time
    
  }
  return total / times.count
}
print(avgSongLength(times: 183, 176, 180, 176, 184, 179, 181, 180, 172, 178))

## In-Out Parameters

var currentGeneratorState = "Off"

func generators(powerOutage: Bool, state: inout String) {
  if powerOutage == true {
    state = "On"
  } else {
    state = "off"
  }
} 
generators(powerOutage: true, state: &currentGeneratorState)
print(currentGeneratorState)

## summary of Function

A function definition consists of a function name followed by optional parameters and a return type.
The function body holds the function’s task.
A function will execute only when it is called.
A return keyword is used to return a value from a function.
A function’s return type is specified in the function definition followed by an ->. If a function does not return any values, it’s return type is Void or the arrow and type are omitted entirely.
A return statement can be omitted if the function consists of only one expression to return. This is called an implicit return.
A parameter is a placeholder for a real value passed into a function. A parameter must be enclosed within () of a function definition and must have a specific type.
An argument is a real value passed in for a parameter in the function call.
A function can accept multiple parameters separated by commas. As many parameters as a function accepts, as many arguments or real values must be passed into the function when it is called.
A function can return multiple values in the form of a tuple.
Swift offers support for wide variety of parameter use cases within a function:
Default Parameter: a parameter that sets a value to the parameter that will be used if an argument is omitted.
Variadic Parameter: a parameter that accepts zero or more values of the parameter’s type.
In-out Parameter: a parameter whose value is passed into a function and modified within the body.


## Creating a Structure

struct Dog {
  var age: Int
  var isGood: Bool
}

## Default Property Values

struct Dog {
  var age = 0
  var isGood = true
}

## Creating an Instance

struct Book {
  var pages = 0
  var title = ""
}

var myFavBook = Book()

## Accessing and Editing Properties

struct Book {
  var pages = 0
  var title = ""
}

var myFavBook = Book()

print(myFavBook.pages)
myFavBook.pages = 640
print(myFavBook.pages)
myFavBook.title = "yasamin"
print(myFavBook.title)

## The Init Method

struct Book {
  var title: String
  var pages: Int

init (title: String, pages: Int){
  self.title = title
  self.pages = pages
}

}
var theHobbit = Book(title: "The Hobbit" , pages: 300)

## Memberwise Initialization

struct Band {
  var genre: String
  var members: Int
  var isActive: Bool
}
var maroon5 = Band(genre: "pop", members: 5, isActive: true)

## Structure Methods


