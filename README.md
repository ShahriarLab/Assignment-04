### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Ans 1 . getElementById() is used to find one element using its id. It always returns only one element because id should be unique.
getElementsByClassName() is used to find elements by class name. It can return many elements.
querySelector() finds the first element that matches a CSS selector.
querySelectorAll() finds all elements that match a CSS selector.


### 2. How do you create and insert a new element into the DOM?
Ans 2 .To create a new element, we use document.createElement().
Then we add text or content to it using textContent or innerHTML.
After that, we insert it into the webpage using methods like appendChild() or prepend().


### 3. What is Event Bubbling? And how does it work?
Ans 3 .Event bubbling means when we click on an element, the event first happens on that element and then moves up to its parent elements.
For example, if a button is inside a div and we click the button, first the button event runs, then the div event runs. This upward movement is called event bubbling.

### 4. What is Event Delegation in JavaScript? Why is it useful?
Ans 4 .Event delegation means adding one event listener to a parent element instead of adding many listeners to child elements.
Because of event bubbling, the parent can handle events from its children.



### 5. What is the difference between preventDefault() and stopPropagation() methods?
Ans 5 .preventDefault() stops the browser’s normal action, like stopping a form from submitting.

stopPropagation() stops the event from moving to parent elements.

So,we  can say that preventDefault() stops browser behavior, and stopPropagation() stops event bubbling.