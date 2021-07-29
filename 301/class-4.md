# Readings: React and Forms

## [React Docs - Forms]()
1. What is a ‘Controlled Component’?🧐
An input form element whose value is controlled by React


2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

3. How do we target what the user is entering if we have an event handler on an input field?
event.target.name.

## [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
1. for decision making in place of longer if and else conditional statements

2. ewrite the following statement using a ternary statement:
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

 console.log()= x===y ? true:false;