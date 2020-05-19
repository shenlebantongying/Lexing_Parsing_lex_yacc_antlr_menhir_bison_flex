Lexer generators such as lex and ocamllex are built on the theory of deterministic finite automata, which you learned in CS 2800.

cs 2800 discrete structure
<https://courses.cs.cornell.edu/cs2800/wiki/index.php/CS_2800_Spring_2020>

# flex-bison-calculator
## usage

Recent version of Flex & Bison. Just use `make`.

r2.l -> flex
r2.y -> bison

Functionality

```
1+1
out:2
```
```
x=3
y=2
x*y

out:3
```

# Useful docs

<https://tomassetti.me/why-you-should-not-use-flex-yacc-and-bison/>

<https://epaperpress.com/lexandyacc/calcl.html>

---

The .tab.c file is somehow "table" file
