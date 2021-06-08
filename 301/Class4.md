## React and Forms

- What is a ‘Controlled Component’?
A Controlled Component is one that takes its current value through props and notifies changes through callbacks like onChange .

![img](https://pbs.twimg.com/media/EKzwxZ4WkAAwjlw.jpg)

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

 no Specifying the value prop on a controlled component prevents the user from changing the input unless you desire so. If you’ve specified a value but the input is still editable, you may have accidentally set value to undefined or null.

- How do we target what the user is entering if we have an event handler on an input field?
   `handleChange(event) {`
    `this.setState({value: event.target.value});`
  `}`

### ternary operator
Why would we use a ternary operator?
 
  Use the ternary operator to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms.

![img](https://scotch-res.cloudinary.com/image/upload/w_1050,q_auto:good,f_auto/v1562952581/jqctyinrganjts991d3w.jpg)

Rewrite the following statement using a ternary statement?
```
let result= ((x===y)? 'true': 'false');
```