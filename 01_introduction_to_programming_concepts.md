# 01: Introduction to Programming Concepts

## Summary
1. **Running the Example Programs**: get set up to work examples in the Mozart Programming System, used in this text
2. **Chapter 1: Introduction to Programming Concepts**

## Running the Example Programs
> p. xxix

1. Install the Mozart Programming System (MPS) (http://mozart-oz.org/).
2. Set up the "Basic system supplements" in the Mozart Oz "run commands" file: .ozrc
   1. Place the contents of http://www.info.ucl.ac.be/people/PVR/ds/booksuppl.oz in a file named .ozrc in your home directory.
3. **Appendix A: Mozart System Development Environment** (pp. 815-818) has some documentation on how to use the MPS.

Please reach out to the **#sf-bookstudy-ctmcp** channel on Slack if you have any problems!

## Chapter 1: Introduction to Programming Concepts
> pp. 1-26

### Exercises
#### Section 1.2: Variables
1. What's the difference between a variable and a value?
#### Section 1.3: Functions 
1. The example function `Fact` on the bottom of p. 2 has an `if... else... end` statement. This statement has no `return` or equivalent syntax. Yet the expression returns a value. How does this work?
2. Um, calling the `Fact` function uses curly braces and no parentheses! How does this work?
#### Section 1.4: Lists
1. Explain the `H|T` syntax.
2. In what way is `H|T` recursive?
3. Which concrete data type (CDT) does `H|T` point at?
4. Explain the `L.1` and `L.2` syntax.
5. In the **Pattern Matching** subsection, on p. 6, the `case` statement is a form of *destructuring binding*, a.k.a. *destructuring assignment*. Explain how this works.
#### Section 1.5: Functions over lists
1. In the **The main function** subsection, on p.7, the example uses `declare` with variable names that remains unbound. The text glosses over the fact that this is *forward declaration*. Explain.

@TODO:
Sections 1.6 onwards
