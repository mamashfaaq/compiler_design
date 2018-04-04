# compiler_design

**STEPS TO COMPILE:**
1. compile the lex file: *flex filename.l*
2. compile the yacc file: *yacc -d filename.y*
3. compile c++ programs: *g++ lex.yy.c filename.tab.c -lfl*
4. execute the file: *./a.out*

**CONCEPTS INCLUDED**
* convert unmatched if to matched if.
* convert for loops and do while loops into while loops.
* construction of syntax tree.
* three address generation & backpatching.
* control flow graph.
* Directed Acyclic Graph(DAG) for basic blocks.
* copy propagation & constant folding.

