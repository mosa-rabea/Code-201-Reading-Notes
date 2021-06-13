 # Problem domain :
## Understanding The Problem Domain Is The Hardest Part Of Programming
### What is the hardest thing about writing code?

There are many common answers to this question:

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable


### A problem domain is the area of expertise or application that needs to be examined to solve a problem. A problem domain is simply looking at only the topics of an individual's interest, and excluding everything else. For example, when developing a system to measure good practice in medicine, carpet drawings at hospitals would not be included in the problem domain. In this example, the domain refers to relevant topics solely within the delimited area of interest: medicine. This points to a limitation of an overly specific, or overly bounded, problem domain. An individual may think they are interested in medicine and not interior design, but a better solution exists outside of the problem domain as it was initially conceived. For example, when IDEO researchers noticed that patients in hospitals spent a huge amount of time staring at acoustic ceiling tiles, which "became a symbol of the overall ambiance: a mix of boredom and anxiety from feeling lost, uninformed, and out of control."


--------------------------------------------------
# Object Literals :
### Several JavaScripts from dyn-web use object literals for setup purposes. Object literals enable us to write code that supports lots of features yet still provide a relatively straightforward process for implementers of our code. No need to invoke constructors directly or maintain the correct order of arguments passed to functions. Object literals are also useful for unobtrusive event handling; they can hold the data that would otherwise be passed in function calls from HTML event handler attributes.
#### There is one drawback: if you are unfamiliar with the syntax, it can be very easy to introduce errors which cause the code to stop working.

---------------------------------------------------
# Object Literal Syntax :
### Object literals are defined using the following syntax rules:
* ### A colon separates property name[1] from value.
* ### A comma separates each name-value pair from the next.
* ### A comma after the last name-value pair is optional.[2]
#### If any of the syntax rules are broken, such as a missing comma or colon or curly brace, a JavaScript error will be triggered. Browser error messages are helpful in pointing out the general location of object literal syntax errors, but they will not necessarily be completely accurate in pointing out the nature of the error.