# javascript
### WHAT IS AN OBJECT? 
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.
IN AN OBJECT: VARIABLES BECOME
KNOWN AS PROPERTIES
If a variable is part of an object, it is called a
property. Properties tell us about the object, such as
the name of a hotel or the number of rooms it has.
Each individual hotel might have a different name
and a different number of rooms. 
IN AN OBJECT: FUNCTIONS BECOME
KNOWN AS METHODS
If a function is part of an object, it is called a method.
Methods represent tasks that are associated with
the object. For example, you can check how many
rooms are available by subtracting the number of
booked rooms from the total number of rooms. This example starts by creating
an object using literal notation.
This object is called hotel which
represents a hotel called Quay
with 40 rooms (25 of which have
been booked).
Next, the content of the page
is updated with data from this
object. It shows the name of the
hotel by accessing the object's
name property and the number
of vacant rooms using the
checkAvail ability() method.
To access a property of this
object, the object name is
followed by a dot (the period
symbol) and the name of the
property that you want.
Similarly, to use the method,
you can use the object name
followed by the method name.
hotel . checkAvailability()
If the method needs parameters,
you can supply them in the
parentheses (just like you can
pass arguments to a function


**Object is a non-primitive data type in JavaScript. It is like any other variable, the only difference is that an object holds multiple values in terms of properties and methods. Properties can hold values of primitive data types and methods are functions.**
A JavaScript object has properties associated with it. A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:
# document object model
The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.It is implemented by all major browser makers, and covers two primary areas:
MAKING A MODEL OF THE
HTM L PAGE
When the browser loads a web page, it
creates a model of the page in memory.
The DOM specifies the way in which the
browser should structure this model using
a DOM tree.
The DOM is called an object model
because the model (the DOM tree) is
made of objects.
Each object represents a different part of
the page loaded in the browser window.
s DOCUMENT OBJECT MODEL
ACCESSING AND CHANGING
THE HTML PAGE
The DOM also defines methods and
properties to access and update each
object in this model, which in turn updates
what the user sees in the browser.
You will hear people call the DOM an
Application Programming Interface (API).
User interfaces let humans interact with
programs; APls let programs (and scripts)
talk to each other. The DOM states what
your script can "ask the browser about the
current page, and how to tell the browser
to update what is being shown to the user
The employee example
The remainder of this chapter uses the employee hierarchy shown in the following figure.

A simple object hierarchy with the following objects:



Employee has the properties name (whose value defaults to the empty string) and dept (whose value defaults to "general").
Manager is based on Employee. It adds the reports property (whose value defaults to an empty array, intended to have an array of Employee objects as its value).
WorkerBee is also based on Employee. It adds the projects property (whose value defaults to an empty array, intended to have an array of strings as its value).
SalesPerson is based on WorkerBee. It adds the quota property (whose value defaults to 100). It also overrides the dept property with the value "sales", indicating that all salespersons are in the same department.
Engineer is based on WorkerBee. It adds the machine property (whose value defaults to the empty string) and also overrides the dept property with the value "engineering".