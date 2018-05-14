* https://www.guru99.com/cyclomatic-complexity.html
* https://github.com/eslint/eslint/blob/master/lib/rules/complexity.js

This explains *Cyclomatic Complexity* as well as uses some diagrams to explain it. I still prefer nPath because I think it includes more branches (params) and is more explicit but still.

CC counts `if`, `for`, `while`, `try`, `switch`.

What it's missing is ternary, template literals, function parameters. I'm pretty sure it only counts the `if` and doesn't count implicit else branches. ie and `if` branch always has an implicit `else` branch.

---

This is important because 
