#learning Journal Day 6

##Constructors

Using an Object Literal

var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};

var person = { firstName:"John",
lastName:"Doe",
age:50,
eyeColor:"blue" };

Using an Object Constructor

function person(first, last, age, eye) {
this.firstName = first;
this.lastName = last;
this.age = age;
this.eyeColor = eye;
}
var myFather = new person("John", "Doe", 50, "blue"); var myMother = new person("Sally", "Rally", 48, "green");
