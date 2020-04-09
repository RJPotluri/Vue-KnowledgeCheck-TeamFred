<p align = "center"><img src = "../vuejs.png" alt = "vue logo"></p>

## Quiz Solutions
Here are the solutions to the knowledge assessment:

### Question 1:
- **B** -- Vue is a progressive front-end javascript framework.

### Question 2
- **A** -- According to [Vue's self comparison](https://vuejs.org/v2/guide/comparison.html#Learning-Curve), **Angular** has a steeper learning curve than Vue.

### Question 3
- **A** -- Double curly braces: `{{ variable + 1 }}` is the correct syntax for binding a javascript expression.

### Question 4
- **TRUE** -- Since computed properties are cached in Vue and revMessage depends on the state of vm.message, vm.Revmessage will indeed be updated whenever vm.message changes.

### Question 5
- **C** -- "You pressed me 1 times" will be the output from Button B. Despite all three buttons (A, B, and C) being made of the same component with the same name (ie. button-counter), they will each maintain there own properties independently. This means that Button B's counter will not be affected by pressing A or C.


