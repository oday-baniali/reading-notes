# Problem Domain, Objects, and the DOM

## Chapter 3: “Object Literals” (pp.100-105)

Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.
 
* IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES
If a variable is part of an object, it is called a property. Properties te ll us about the object, such as the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms.

* IN AN OBJECT: FUNCTIONS BECOME
KNOWN AS METHODS
If a function is part of an object, it is called a method.
Methods represent tasks that are associated with
the object. For example, you can check how many
rooms are available by subtracting the number of
booked rooms from the total number of rooms.

Programmers use a lot of name/value pairs:
• HTML uses attribute names and values.
• CSS uses property names and values. In JavaScript:
• Variables have a name and you can assign them a value of a string, number, or Boolean.
• Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number    and a value.)
• Named functions have a name and value that is a set of statements to run if the function is called.
• Objects consist of a set of name/value pairs (but the names are referred to as keys).

## Chapter 5: “Document Object Model” (pp.183-242)

The browser represents the page using a DOM tree. DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes. You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax. Whenever a DOM query can return more than one node, it will always return a Nadel i st. From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques. An element node can contain multiple text nodes and child elements that are siblings of each other.
In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery). Browsers offer tools for viewing the DOM tree.
