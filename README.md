<p align = "center"><img src = "images/vuejs.png" alt = "vue logo"></p>

## Knowledge Recap
* [Question 1](#question-1)
* [Question 2](#question-2)
* [Question 3](#question-3)
* [Question 4](#question-4)
* [Question 5](#question-5)

## Question 1
What is Vue?

- A) A python-based web framework
- B) A progressive front-end javascript framework
- C) An HTML and CSS library for front end development 

## Question 2
When compared to React and Angular, which is the following is **FALSE**?

- A) Vue has a steeper learning curve than Angular
- B) Like React, Vue provides a virtual DOM (document object model)
- C) Vue generally takes up less space than React and Angular

## Question 3
Which of the following has correct syntax for binding a javascript expression in Vue?

- A) `{{ variable + 1 }}`
- B) `<variable += 1>`
- C) `<div> {v-bind:id="var"}</div>`

## Question 4
Consider the following code excerpt:

```
var vm = new Vue({
 data: {message: "Hi" },
 computed: {
   revMessage: function() {
     return this.message.reverse() 
    }
  }
})
```

Based on the code above, is the following statement **TRUE** or **FALSE**:
Whenever vm.message changes, vm.revMessage will automatically be updated as well.


## Question 5
Consider the following component:

```
// Define a new component called button-counter
Vue.component('button-counter', {
  data: function () {
    return {
      count: 0
    }
  },
  template: '<button v-on:click="count++">You clicked me {{ count }} times.</button>'
})
```

And the following page which implements the above component:

```
<div id="components-demo">
  <button-counter>Button A</button-counter>
  <button-counter>Button B</button-counter>
  <button-counter>Button C</button-counter>
</div>
```

If Button A is pressed twice, producing the output "You clicked me 1 times" followed by "You clicked me 2 times," what will the next output be if Button B is pressed immediately following the second press of A?
- A) "You pressed me 3 times"
- B) "You pressed me 2 times"
- C) "You pressed me 1 times"
