# Answers

1. What is React JS and what problems does it solve? Support your answer with concepts introduced in class and from your personal research on the web.

    A javascript libraries combined that allows for easier DRY code by creating components/functions that can be reused throughout the app using html, css, and javascript in one place

1. Describe component state.

    state is a tuple constant that holds a value and a callback function for use and change throughout the code. 

1. Describe props.

    Parameters passed to a component as properties for passing data from a parent component to a child component

1. What are side effects, and how do you sync effects in a React component to changes of certain state or props?

    Side Effects are actions that take place after the component has rendered. Typically used for using an axios get request. 

    In order to sync effects, you would add an array as the second argument of the useEffect and inside the array you add the state
    variables that you want it to monitor and run the effect when it changes.
