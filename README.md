Requirements - We will need lex, Yacc and SPIM emulator( to test MIPS code).

Here is a list of files we have developed and a short description of what happens in each files :-

cGrammer : Grammer used for this assignment

clexer.l : lexer file for defining valid language tokens

cparser.y : Yacc based parser. Checks for symmentic errors and generates Abstract Syntax Tree and outputs final MIPS code.

CtoMIPS.c : takes AST as input and generates MIPS code into mips_code.s

symbolTable.c : defines helping functions used for creating Symbol Table.

definition.c : helping functions for generating AST.

definition.h : defines structure for AST and Symbol Table.

test.c : some test programs for testing.
