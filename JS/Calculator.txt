// Version 1: Basic calculation with default values

var Head1 = console.log("Default Values")

var number1 = 24
var number2 = 45

var sum = console.log("The Sum is: " + (number1 + number2))
var sub = console.log("The Subraction is: " + (number1 - number2))
var mul = console.log("The Multiple is: " + (number1 * number2))
var div = console.log("The Division is: " + (number1 / number2))

// Version 2: Get input numbers from the user and performing the calculation

var Head2 = console.log("Dynamic Values")

var number1 = window.prompt("Enter the First Number:")
var number2 = window.prompt("Enter the Second Number")

var sum = console.log("The Sum is: " + (number1 + number2))
var sub = console.log("The Subraction is: " + (number1 - number2))
var mul = console.log("The Multiple is: " + (number1 * number2))
var div = console.log("The Division is: " + (number1 / number2))