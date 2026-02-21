Answers to Questions

1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

. getElementById() → Selects one element by ID.

. getElementsByClassName() → Selects multiple elements by class (HTMLCollection).

. querySelector() → Selects first matching element using CSS selector.

. querySelectorAll() → Selects all matching elements (NodeList).



2. How do you create and insert a new element into the DOM?

. Create element → document.createElement("tag")

. Add content → element.textContent = "Text"

. Insert it → parent.appendChild(element)



3. What is Event Bubbling? And how does it work?

. Event Bubbling means an event starts from the target element and then moves upward to its
parent elements.

  Example:
   Click on a button → event goes to button → div → body → document.



4. What is Event Delegation in JavaScript? Why is it useful?

. Event Delegation means adding an event listener to a parent element to handle events of its child elements.

   Useful because:

       . Fewer event listeners

       . Better performance

       . Works for dynamically added elements



5. What is the difference between preventDefault() and stopPropagation() methods?

. preventDefault() → Stops default browser action (e.g., form submit, link open).

. stopPropagation() → Stops the event from bubbling up to parent elements.

