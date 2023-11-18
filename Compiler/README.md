#### This is a basic compiler that converts LISP code to JS code
---
This is a simple 4 step process:
1. Lexical Analysis
    * Breaks input code (string) into basic syntax of the language(array of objects)
    
3. Syntactic Analysis (create an abstract syntax tree)
    * Transforms tokens (array of objects) into an AST (tree of objects) which represents our program
3. Transformation = Transforms our original LISP AST into our target Javascript AST
4. Code Generation - Transforms our target AST )object of objects into actual code (string)
---

Credit to this [website](https://citw.dev/tutorial/create-your-own-compiler?p=10)

---
Instructions:
* Install node
* To run program:\
   `node index`
