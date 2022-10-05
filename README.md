# brainfuck-interpreter
🤯 A brainfuck interpreter I created to practice rust
* [Brainfuck is an esoteric programming language created in 1993 by Urban Müller. Notable for its extreme minimalism, the language consists of only eight simple commands, a data pointer and an instruction pointer.](https://en.wikipedia.org/wiki/Brainfuck)

# Brainfuck characters
```
    > move pointer to right by 1
    < move pointer to left by 1
    + increment the value of cell by 1
    - increment the value of element by 1
    . print value of current cell
    , take input to current cell
    [ ] loop, +++[ -] counter of 3 counts as it has 3 '+' before it and - decrements count variable by 1 value

```

# Hello World example!
`++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.`
![image](https://user-images.githubusercontent.com/84540554/194183461-1633ad37-d040-4fe4-9e00-108b0ee75bf6.png)

```
+++++ +++++             initialize counter (cell #0) to 10
[                       use loop to set the next four cells to 70/100/30/10
    > +++++ ++              add  7 to cell #1
    > +++++ +++++           add 10 to cell #2 
    > +++                   add  3 to cell #3
    > +                     add  1 to cell #4
    <<<< -                  decrement counter (cell #0)
]                   
> ++ .                  print 'H'
> + .                   print 'e'
+++++ ++ .              print 'l'
.                       print 'l'
+++ .                   print 'o'
> ++ .                  print ' '
<< +++++ +++++ +++++ .  print 'W'
> .                     print 'o'
+++ .                   print 'r'
----- - .               print 'l'
----- --- .             print 'd'
> + .                   print '!'
> .                     print '\n'
```
