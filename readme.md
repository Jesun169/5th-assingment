Q1- What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

getElementById - Selects a single element with the given id.

getElementsByClassName - Selects all elements with the given class.

querySelector - Selects the first element that matches the CSS selector.

querySelectorAll - Selects all elements that match the CSS selector.

Q2- How do you create and insert a new element into the DOM?
Ans: First create a new element (document.createElement()) and than add a meaningful text or attributes. Put it inside DOM so it becomes visible.

Q3- What is Event Bubbling and how does it work?
Ans: Event Bubbling means that when an event (like click) happens on an element, the event first runs the handler on that element, and then it “bubbles up” to its parent, then grandparent, and so on, until it reaches the final window.

Q4- What is Event Delegation in JavaScript? Why is it useful?
Ans: Instead of attaching event listeners to multiple child elements, attach one listener to a parent element and use event bubbling to catch events is Event Delegation in JavaScript.

- It Saves memory & improves performance.
- Works even for dynamically added elements.

Q5- What is the difference between preventDefault() and stopPropagation() methods?
Ans: 
preventDefault()
Stops the browser’s default behavior for an element.

stopPropagation()
Stops the event from bubbling up / down to other event listeners.