In no particular order. Based on [Real world functional programming in JS](https://github.com/haskellcamargo/js-real-world-functional-programming)

# Commandments
1. Functions over data, over classes, over people, over humanity, over everything. Functions are life. Functions are ethical. Functions are moral. Functions are more important than your family, your kids, your dog.
    - Initial data? A function returns dat.
    - Need to determine if something is true? A function returns dat.
1. Write only pure functions
    - No side effects
    - Do not mutate state in any scope of any funciton
1. Write point free code
    - http://lucasmreis.github.io/blog/pointfree-javascript/
1. Every function is small and does one thing
1. Ternaries & Predicates over conditionals
1. Every function always returns something
    - Always the same thing
    - Always a default if failure or something
        - If default easier to write predicates.
1. Unit test everyting always now and forever amen.
1. Fewer params over more params
    - Not nessessarily to the user
1. Write functions where calling order doesn't matter.
1. Memoize as much as makes sense.
1. No more imperative loops. Sorry, no more. Let go of those crutches.
1. Use algebraic data types for writing side effected functions.

# Extra Links
* https://stackoverflow.com/questions/33027305/why-are-folktale-and-ramda-so-different
* https://github.com/ramda/ramda-fantasy/issues/105
* http://folktale.origamitower.com/docs/v2.1.0/
