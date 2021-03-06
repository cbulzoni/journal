---
layout: post
title: Things I learned from The Ruby Koans
---

Here are some things I learned from [The Ruby Koans](http://rubykoans.com/):

 - Ruby programmers tend to favor the shovel operator (<<) over the # plus equals operator (+=) when building up strings
 - The shift() method removes the first item whereas the pop() method removes the last item in an array
 - ArgumentError is raised when a method is called with an incorrect number of arguments
 - If there is no explicit return in a method, it will return the bottom line
 - Most everything in Ruby is true (except for false and nil)
 - The each method can also be called using curly brace blocks
 - A lot of the operations in the about_iteration koan seemed very useful (collect, select, find, etc.)
 - Two dots (..) create inclusive ranges whereas three dots (...) exclude the high value
 - Classes can be reopened and new methods can be added while still preserving existing methods
 - You can define methods on individual objects

These are some outstanding questions I had based on the Ruby Koans:

 - I'm not sure I understand the utility/functionality of a private method
 - Is there a more efficient way to do the triangle method than using and/or combinations?
 - How does the _inject_ method work in the about_iteration koan?
 - I'm having trouble following the about_sandwich koan
 - I'm curious if there is a more efficient solution to the about_scoring_project than I came up with
 - Not sure I totally follow the _super_ method in about_inheritance. It just looks for a method with a matching name from the parent class?

These are the Koans I would like to review more closely:

 - about_exceptions
 - about_blocks
 - about_classes
 - about_open_classes
 - about_modules
 - about_scope
 - about_class_methods
 - about_message_passing
 - about_proxy_object_project

Note: looks like theres a [Ruby Koans YouTube series](https://www.youtube.com/watch?v=H0jPLFE17do&list=PL3vpzVxKa3PiKKQf5HeXJJGZO-M1MVyfi) that walks through each koan



