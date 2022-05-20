---
layout: post
title:  "every() method in JavaScript"
---

Today I learned about a handy method in JavaScript called .every(). I'm sure I had learned about this during the Scrimba JavaScript bootcamp, but I ran into a scenario where I needed to check whether all elements in an array met a certain condition. After stumbling through some potential solutions, I discovered that the .every() method does exactly that. An example use case would be as follows:

someArray.every(x => x >= 10)

This would look at all items in the array to see if they were greater than or equal to ten, returning a boolean value. I'm certain there are many other ways to accomplish this in JavaScript, but I found this method very handy.
