---
layout: post
title:  "Props and State in React"
---

I am working through the React tutorial on Scrimba and one thing that I had to wrap my head around was the distinction between Props and State. 

**Props** provides a way to pass saved variables into a component. Props are immutable, meaning that if you update those saved variables (perhaps using some sort of event handler), they will not update in the component. 

**State** on the other hand is mutable. When you declare a state using React.useState(), it automatically creates an array with a value and a function. You can use that function to dynamically update the value within the component. This makes state very useful anytime you want an event handler to update a variable, and have the updated version displayed when the component is re-rendered.
