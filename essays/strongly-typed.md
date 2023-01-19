---
layout: essay
type: essay
title: "Why I Like Strongly Typed Languages"
# All dates must be YYYY-MM-DD format!
published: true
labels:
  - Engineering
---


  One of the things that I first noticed about using Javascript is the fact that there are no strongly typed variables. Instead, you have a situation where all variables can be declared with no real specification for what that variable is. While I can see how this may simplify things in some ways, and allow for greater flexibility when using code, I also feel that this could lead to many issues if not handled properly. 

  For example, one function may accept a numerical input, but we cannot specify whether it is accepting an integer or a float. In a strongly typed language like C, a variable can be relied on to be either a float, an integer or whatever it was declared as, and therefore can be expected to behave in certain ways when interacted with. In Javascript, though, a variable could be anything, and therefore behave in unexpected ways when accessed. You could then have a situation where one's code compiles and displays no errors, but does not produce the desired effect. In a strongly typed language, this would be more likely to throw an error. 
  
  When I work, I think it's much easier to fix a compiler error than comb over every inch of code to find where the unintended behavior is. Having said all of this, regardless of the language, careful consideration of variable types and their consequences is always necessary. Of course, there are benefits to having a weakly typed language as well, like the flexibility it offers when passing things to functions. However I am still unsure if the advantages outway the disadvantages.

