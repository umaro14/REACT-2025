# REACT-2025

# Babel ==> translate other code into JavaScript.

const button = <button>Hello</button>  ==> this is JSX.
Our Browser does not understand JSX it only understands JavaScript. So we need to convert JSX into JavaScript. 
This is done by an external library called Babel.
---------------------------------------------------------------------------------------------------

# Guard Operator(&&)
The && operator is called the guard operator. It is used to prevent the execution of a function if
a condition is not met.
-if value-1 is true, the result will be value-2
-if value-1 is false, the result will be false.
---------------------------------------------------------------------------------------------------

# Copy
In react we shoul not modify the data directly, we should always create a COPY, then modify the copy.
Do not use the DOM manually (React is maneging the website ).

-----------------------------------------------------------------------------------------------------
# Lifting the State Up
Lifting the state up is a technique used in React to manage state in a hierarchical way. It
involves moving the state from a child component to a parent component, and then passing the state
down to the child components that need it.