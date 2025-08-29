1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
ans:document.getElementById("myId") A single element object (or null if not found),
document.getElementsByClassName("myClass") An HTMLCollection (live, auto-updated when DOM changes).
document.querySelector("CSS selector") A single element object (or null if not found).

2.How do you create and insert a new element into the DOM?
ans:createElement() only creates it in memory, not yet visible on the page, can also set attributes, classes, or styles

3.What is Event Bubbling and how does it work?
ans:When an event occurs on a DOM element, it first triggers on the target element (the element where the event happened).

4.What is Event Delegation in JavaScript? Why is it useful?
ans:Instead of attaching an event listener to every child element, you attach a single listener to a parent element. Then, inside the listener, you check which child triggered the event using the event.target property.

5.What is the difference between preventDefault() and stopPropagation() methods?
ans: preventDefault() = Stops the default action associated with an event from happening.
stopPropagation() = Stops the event from bubbling up (or capturing down) the DOM tree.