# SLR-parser
Here simulation of SLR parser will be shown. SLR is simple LR. It is smallest class of grammar having few number of states. SLR is very easy to construct and is similar to LR parsing. There is only difference of parsing table. In SLR parser, we perform a reduction implied by a valid item with a dot at the right end, provided the lookahead symbol can follow the head of that production in some sentential form. The grammar is SLR, and this method can be applied, if there are no parsing-action conflicts; that is, for no set of items, and for no lookahead symbol, are there two productions to reduce by, nor is there the option to reduce or to shift.
An SLR parser is quite efficient at finding the single correct bottom-up parse in a single left-to-right scan over the input stream, without guesswork or backtracking. The parser is mechanically generated from a formal grammar for the language. To construct the parsing table, we have followed the use of augmented grammar also along with some other methods and techniques which can be used in the process of parsing.
Language Used: Python
Input:
1.	Number of productions
2.	Enter the productions of grammar
3.	Input string
Output:
	In the output as already specified, requirement is of a such a system that perform computation of LR(0) canonical items and SLR parser to parse on a string. So the following output will be produced:
1.	Given grammar
2.	Augmented grammar
3.	Terminals present the grammar
4.	Non-terminals present in the grammar
5.	Symbols present in the grammar
6.	First of each non-terminal in augmented grammar
7.	Follow of each non-terminal in augmented grammar
8.	Canonical LR(0) items such that of form I0, I1, I2, etc.
9.	Closure for each state
10.	If there will be any error, it will be given.
11.	Parsing table
12.	Simulation of SLR parser will be given in the form of a table which contains steps, stack, input and action performed in each step.
Whatever input will be given, it will be processed by different functions containing different algorithms such that they are in cooperation with each other. 
At the end error will be checked with different examples whether it is giving correct output or not, it will be checked manually and later on by observation.
