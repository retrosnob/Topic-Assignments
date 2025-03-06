<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

<script type="module">
    import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.esm.min.mjs';
    mermaid.initialize({ startOnLoad: true });
</script>


# Topic 6 Fundamentals of Computer Systems

1. Define _hardware_.
1. Define _software_.
1. Define _application sofware_.
1. Define _system sofware_.
1. Describe the purpose of:
    1. Operating systems
    1. Utilities
    1. Libraries
    1. Translators
1. State four resources managed by the operating system
1. Describe one advantage of a compiler and one disadvantage of an interpreter.
1. Describe one advantage of an interpreter and one disadvantage of a compiler.
1. Tick the box for which the statement is true:

    | Statement | Compiler | Intepreter |
    |-----------|----------|------------|
    | It translates the entire source code into machine code before execution. |  |  |
    | It executes the source code line by line, translating each line just before executing it. |  |  |
    | Programs generally run faster after translation because the machine code is already generated. |  |  |
    | It requires less memory during execution since it doesn't need to keep the source code in memory. |  |  |
    | Errors are reported after analyzing the entire source code, making debugging more challenging. |  |  |
    | It stops execution at the point of an error, allowing for easier debugging. |  |  |
    | The source code is kept hidden from the end user, as only the machine code is distributed. |  |  |
    | It makes programs more portable since the source code can be executed on any system with the appropriate software. |  |  |
    | Optimization techniques are applied to improve the performance of the generated machine code. |  |  |
    | It requires the source code to be present every time the program is executed. |  |  |
    | It generates an intermediate object code that can be linked with other modules. |  |  |
    | The program execution can be slower because translation happens during runtime. |  |  |
    | Syntax analysis is completed before execution begins, ensuring all syntax errors are caught upfront. |  |  |
    | It allows for interactive execution and testing of code snippets. |  |  |
    | The translated code is usually specific to a particular type of computer architecture. |  |  |
    | It requires a runtime environment to execute the translated code. |  |  |
    | Once translated, the program can be executed multiple times without retranslation. |  |  |
    | It often uses less storage space since no machine code is saved. |  |  |
    | The translation process typically takes longer since the entire source is analyzed in one go. |  |  |
    | It facilitates dynamic typing and late binding, allowing variables to change types during execution. |  |  |
    | It generally produces more optimized machine code, leading to better performance. |  |  |
    | It is commonly used in scripting and web-based applications. |  |  |
    | The output of the translation is a standalone executable file. |  |  |
    | It provides better error diagnostics by pointing to the exact line where an error occurs. |  |  |
    | The development cycle involves separate steps of writing, translating, and linking. |  |  |
    | It allows on-the-fly code modifications, making it useful for rapid prototyping. |  |  |
    | Security is enhanced since the end user cannot easily view or modify the source code. |  |  |
    | It is typically slower in execution speed due to the overhead of runtime translation. |  |  |
    | Memory management can be more efficient since the program structure is fully analyzed before execution. |  |  |
    | It is often used for educational purposes to help beginners learn programming concepts. |  |  |

1. Explain how an assembler is different from a compiler or translator.
1. Describe the characteristics of a virtual machine and explain why virtual machines were developed.
1. Tick the boxes to match the statements:

    |  | Source code | Object code |
    |---|---|---|
    | Stored in a text file |  |  |
    | Stored in a binary file |  |  |
    | Can be executed without translation |  |  |
    | Must be translated before execution |  |  |
    | Contains low-level instructions |  |  |
    | Contains high-level instructions |  |  |

1.  State the logic gate that has the truth table:

    | A | B | Out |
    |-----|-----|-----|
    | 0 | 0 | 0 |
    | 0 | 1 | 0 |
    | 1 | 0 | 0 |
    | 1 | 1 | 1 |

1.  State the logic gate that has the truth table:

    | A | B | Out |
    |-----|-----|-----|
    | 0 | 0 | 0 |
    | 0 | 1 | 1 |
    | 1 | 0 | 1 |
    | 1 | 1 | 0 |

1.  State the logic gate that has the truth table:

    | A | B | Out |
    |-----|-----|-----|
    | 0 | 0 | 1 |
    | 0 | 1 | 0 |
    | 1 | 0 | 0 |
    | 1 | 1 | 0 |

1.  State the logic gate that has the truth table:

    | A | B | Out |
    |-----|-----|-----|
    | 0 | 0 | 0 |
    | 0 | 1 | 1 |
    | 1 | 0 | 1 |
    | 1 | 1 | 1 |

1.  State the logic gate that has the truth table:

    | A | B | Out |
    |-----|-----|-----|
    | 0 | 0 | 1 |
    | 0 | 1 | 1 |
    | 1 | 0 | 1 |
    | 1 | 1 | 0 |

1.  State the logic gate that has the truth table:

    | A | Out |
    |-----|-----|
    | 0 | 1 |
    | 1 | 0 |
    
1.  Write the boolean expression that corresponds to this truth table:

    | A | B | C | Out |
    |-----|-----|-----|
    | 0 | 0 | 0 | 0 |
    | 0 | 0 | 1 | 1 |
    | 0 | 1 | 0 | 0 |
    | 0 | 1 | 1 | 0 |
    | 1 | 0 | 0 | 1 |
    | 1 | 0 | 1 | 1 |
    | 1 | 1 | 0 | 0 |
    | 1 | 1 | 1 | 0 |

1.  Simplify the following Boolean expression:
    $$
    \overline{\overline{A}+B}.B
    $$
    For other further Boolean algebra practice, see 
        * [AQA Boolean Algebra Document](https://tonbridgeschool4.sharepoint.com/:b:/r/sites/ComputerScience/Shared%20with%20Students/A%20Level/Files/Boolean%20Algebra.PDF)
        * [Topic 1](Topic_01.html)
1. Distribute over the bracket:
    $$
    X.(Y+Z)
    $$
1. Distribute over the bracket:
    $$
    P+(Q.\overline{R})
    $$
1. Factorise:
    $$
    (A.C)+(\overline{B}.A)
    $$
1. Factorise:
    $$
    (X+Y).(Y+Z)
    $$