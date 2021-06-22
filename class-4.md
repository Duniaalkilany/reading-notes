# **React and Forms**
![img](https://res.cloudinary.com/practicaldev/image/fetch/s--KpQnReJ9--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://i1.wp.com/blogreact.com/wp-content/uploads/2020/03/forms.jpg%3Ffit%3D750%252C393%26ssl%3D1)
# **React Docs - Forms**


## **What is a ‘Controlled Component’?**


### Controlled Component is one that takes its current value through props and notifies changes through callbacks like onChange . A parent component "controls" it by handling the callback and managing its own state and passing the new values as props to the controlled components.
### An input is said to be “controlled” when React is responsible for maintaining and setting its state. The state is kept in sync with the input’s value, meaning that changing the input will update the state, and updating the state will change the input.
### In HTML, form elements such as < input>, < textarea>, and < select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().




## **Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

### Since the value attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.
### the continuous update loop of controlled components makes it possible to perform continuous validation on inputs as the user types. A handler attached to an input’s onChange event will be fired on every keystroke, allowing you to instantly validate or format the value.
### With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.


## **How do we target what the user is entering if we have an event handler on an input field?**

### Using event.target.value, the value can be fetched and further processed for submitting the form values to the server.

### **Example:**

![ex1](imgs/ex8.png)

# **The Conditional (Ternary) Operator Explained**

## **Why would we use a ternary operator?**

## it manage us to write condition codedo in just one line of code so to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms.

## **Rewrite the following statement using a ternary statement:**

  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
## by using this :

  condition ? value if true : value if false

## so the Solution :

x===y?console.log(true):console.log(true)

## Things I want to know more about
 
### How can I builging and dealing with forms in react .


## Sources:
* [React Docs - Forms](https://reactjs.org/docs/forms.html)
* [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)


