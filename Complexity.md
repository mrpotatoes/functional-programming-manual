* https://www.guru99.com/cyclomatic-complexity.html
* https://github.com/eslint/eslint/blob/master/lib/rules/complexity.js

This explains *Cyclomatic Complexity* as well as uses some diagrams to explain it. I still prefer nPath because I think it includes more branches (params) and is more explicit but still.

CC counts `if`, `for`, `while`, `try`, `switch`.

What it's missing is ternary, template literals, function parameters. I'm pretty sure it only counts the `if` and doesn't count implicit else branches. ie and `if` branch always has an implicit `else` branch.

---

This is important because we want [easily] testable code. Testable code is quality code. Quality code makes us look good because we can push things with confidence.

The more branches that a function has the more we should be testing but usually do not. We'll test "the most probable" test cases. This means that we will/do not have great condifidence in our code. We aren't assured of it's quality.

* The more complex it is, the more difficult it becomes to read and:
    * The harder it is to organize.
    * The harder it is to name variables, loops, lambda functions et al.
* The more complex it is the longer it is.
* The longer it is the more difficult it is to read.
* The more complex the more branches it has
    * The more branches the more difficult it is to read
    * The more difficult it is to test.
    * The more a developer has to maintain in their memory of the flow of code
* (Often) The more complex the more dependancy management one has to do

All this leads to more tests to write and more difficult tests to write.
