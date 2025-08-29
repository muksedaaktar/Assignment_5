# Answer all of the Given Question

## Q-1: What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Ans:
getElementById: It selects a unique element by its id and returns one element . If it not found the selected element , it had returned null.
getElementsByClassName: It selects all elements with a given class and returns a live HTMLCollection. It is not an array but like an array.
querySelector/querySelectorAll: querySelector and querySelectorAll are both select elements using any valid CSS selector. The querySelector selects first matching element and querySelectorAll selects all 
matching elements. It returns a static NodeList.

## Q-2: How do you create and insert a new element into the DOM?
Ans:
For creating a new element into the DOM I will use document.createElement() method and for inserting a new element into the DOM I will use appendChild() method. I can also use insertBefore(), append(), 
prepend() this method for where specifically  insert the method.


## Q-3: What is Event Bubbling and how does it work?
Ans:
Event bubbling means that when an event occurs on a nested element (child), it “bubbles up” to its parent elements, all the way up to the root (document), unless explicitly stopped. 
Working process: At first, event starts at the top (document) and travels down to the target element. Then, event reaches the target element (where the event actually occurred) and last, 
Event travels back up from the target element to the ancestors.

## Q-4: What is Event Delegation in JavaScript? Why is it useful?
Ans:
Event Delegation means attaching a single event listener to a parent element instead of attaching listeners to multiple child elements. It is usefull for efficiency, clean code and avoid reattach listeners.

## Q-5: What is the difference between preventDefault() and stopPropagation() methods?
Ans:
The difference between preventDefault() and stopPropagation() methods is preventDefault() prevents the default action of an HTML element from occurring and stopPropagation() stops the event from bubbling up
(or capturing down) the DOM tree.


