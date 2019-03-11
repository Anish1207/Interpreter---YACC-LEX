# Interpreter-using-lex-and-yaac
This is an implementation of a simple interpreter using lex and yaac for evaluating a given cfg
## Building the interpreter
yacc -y -d yacc.y

lex lex.l

gcc lex.yy.c y.tab.c definition.c -o compile
