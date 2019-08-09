 What are the required parts of class components?

Class components make use of the ES6 class syntax. Since classes can have methods, these components can make use of life cycle methods like for example componentWillMount and componentDidMount. Have a look at the above example, rewritten as a ES6 class component. Therefore, class components extend from React.Component, and you have to use the this keyword to access props (and also other functions you declare inside the component).

 Name at least three lifecycle methods?

Mounting – Birth of your component
Update – Growth of your component
Unmount – Death of your component

 Why are forms used so often in web applications and software?

Because of the following:

1. Store input in the container component’s state. Validate them after the user hits submit and before you actually submit the data to a remote endpoint.
2. Store input in the container component’s state or React  and validate them on the fly when the user manipulates the inputs.

3. Use a third party library that already ships form, input and error components out of the box, plus hook up third party validation on top of it.

 What advantages are there by using a forms library like Formik?

Formik helps with the major problems of handling forms in React:

Transforming props to form state
Validation and error messages
Handling form submission

 Why do we write tests for our apps?

 Data Driven Testing (DDT) improves the quality of the code. It identifies every defect that may have come up before code is sent further for integration testing. Writing tests before actual coding makes you think harder about the problem. It exposes the edge cases and makes you write better code