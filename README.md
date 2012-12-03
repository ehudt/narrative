narrative
=========

Want to write a program? Want to write a story? Why not both?

Many people think that in order to be a fine programmer, one must also be a good writer. narrative programming language takes this notion to the next level - All programs in narrative are stories, and should be judged by their literary quality as much as by their functionality.

Language syntax
===============

Technically speaking, narrative presents an alternative, more creative syntax to the widely-used brainfuck programming language. Only, instead of being minimalistic, it is quite the opposite. Every word in your story represents a single instruction (equivalent to a brainfuck instruction), determined by its first letter.

Specification
=============

  Opening letter    brainfuck equiv.
  --------------    ----------------
    e, r, u, v            +
    t, d, m ,k            -
    a, l, w, j            >
    o, c, f, x            <
    i, g, q               [
    n, y, z               ]
    s, p                  .
    h, b                  ,
    
Example
=======

The following program prints "Hello World!":

