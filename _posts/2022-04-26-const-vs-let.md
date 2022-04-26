---
layout: post
title:  "Let vs. Const Variables in JavaScript"
---

After getting an intro to the JavaScript language via the Scrimba bootcamp, I was intruiged by the concept of let vs. const variables. I recall learning in Ruby that it is customary to capitalize the first letter in a variable if it is supposed to be a constant, but Ruby won't prevent you from changing them. In JavaScript, however, you can declare a variable with either var, let or const. Var declarations are globally scoped or function scoped, which can make them tricky to work with, so it is more common to use either let or const. 

Let and const declarations are both block scoped, meaning they are only available for use within the block they are scoped. However let declarations can be updated throughout your code, whereas variables declared with const cannot. This presents a new challenge in my progression as a developer, as it requires some thought be given to whether each variable declared should be something that can be changed. While this adds an extra step, I can definitely see the value in helping to prevent bugs. In the tutorials it was recommended that we use const when in doubt, as you are more likely to avoid unwanted bugs and it improves the readability of your code.
