#Learning Journal Day 8

####TODAY WE LEARNED

Adding event listener and handler

listener The object that receives a notification (an object that implements the Event interface) when an event of the specified type occurs. This must be an object implementing the EventListener interface, or simply a JavaScript function.

Registering on-event handlers

The on-event handlers are a group of properties offered by DOM elements (both interactive - such as links, buttons, images, forms - and not), the base document itself, and so on, to help manage how that element reacts to events like being clicked, detecting pressed keys, getting focus, etc. -- and they are usually named accordingly, such as onclick, onkeypress, onfocus, etc.

You can specify an on<...> event handler for a particular event (such as click) for a given object in different ways:

Using an HTML attribute named on{eventtype} on an element, for example: , Or by setting the corresponding property from JavaScript, for example: document.getElementById("mybutton").onclick = function(event) { ... }.
