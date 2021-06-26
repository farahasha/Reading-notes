## Object Literals

 > Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names


## WHAT IS AN OBJECT? 

1- JavaScript object is a standalone entity that holds multiple values in terms of properties and methods.
2-JavaScript object is a standalone entity that holds multiple values in terms of properties and methods.
3-An object can be created using object literal or object constructor syntax.
4-Object literal:
`var person = { 
    firstName: "James", 
    lastName: "Bond", 
    age: 25, 
    getFullName: function () { 
        return this.firstName + ' ' + this.lastName 
        } 
};`

5-Object constructor:
`var person = new Object();                
person.firstName = "James";
person["lastName"] = "Bond"; 
person.age = 25;
person.getFullName = function () {
        return this.firstName + ' ' + this.lastName;
    };`

6-Object properties and methods can be accessed using dot notation or [ ] bracket.
7-An object is passed by reference from one function to another.
8-An object can include another object as a property.
\

### Object initializer
Objects can be initialized using new Object(), Object.create(), or using the literal notation (initializer notation). An object initializer is a comma-delimited list of zero or more pairs of property names and associated values of an object, enclosed in curly braces ({}).

![object](https://1.bp.blogspot.com/-eHICkeDNwmg/XInHyvSvIVI/AAAAAAAAACs/VaP1WfL3LhYs2DgMxmdaLaq0F6bD_HCPACLcBGAs/s1600/definig%2Bwith%2Bkey%2Bvalue%2Bpair.JPG)

--------------------------------------------------------------

### Document Object Model

#### The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.