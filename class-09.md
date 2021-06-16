## Forms and Events
What are the form events?
Events are things that happen to objects, such as the clicking of a command button or the opening and closing of a form, etc. These events trigger an action to be carried out.

* What are all the JavaScript events?
DOM event types
mouse events ( MouseEvent ): mousedown, mouseup, click, dblclick, mousemove, mouseover, mousewheel, mouseout, contextmenu.
touch events ( TouchEvent ): touchstart, touchmove, touchend, touchcancel.
keyboard events ( KeyboardEvent ): keydown, keypress, keyup.
form events: focus, blur, change, submit.


- We can collect info from client by forms,by putting it inside form.
- Each info in form had a name and value.
- each form control is givin a name,and the text the user types in or the values of thre options they select are sent to the server.
- Html have a new form that is easyer to be used

Attaching events to templates
Event listeners are added to templates in much the same way as helpers are: by calling Template.templateName.events(...) with a dictionary. The keys describe the event to listen for, and the values are event handlers that are called when the event happens.

In our case above, we are listening to the submit event on any element that matches the CSS selector .new-task. When this event is triggered by the user pressing enter inside the input field, our event handler function is called.

The event handler gets an argument called event that has some information about the event that was triggered. In this case event.target is our form element, and we can get the value of our input with event.target.text.value. You can see all of the other properties of the event object by adding a console.log(event) and inspecting the object in your browser console.
