# drracket
racket practice for GWC

LAMBDA CALCULUS

compiler: a compiler can take something that looks like plain arithmetic and convert it automatically into a format that the computer can execute.

interpreter: an interpreter is similar, although it performs the actions described in a humanwritten program directly; there is no internediate step that converts it all the way down to a computer format.

compilers and interpreters are software.

FORTRAN

ALGOL 60 

Lisp-a family of programming languages

Every open parenthesis is followed by an operator. Left parentheses are open parentheses; right parentheses are closed parentheses.

By adding a quote to the left of a piece of Lisp code, we turn it into a piece of data.

Functions: objects that understand only one message are functions, "run your code on the following arguments"

assignment standards
jumps in control flow

syntactic sugar: shorthand for a bom bination of concepts from this tiny core language

Scheme is a prototyped Lisp language.

PDE program development environment
IDE interactive development environment

Racket has many flavors, beginner languages are called teaching languages. 

Definitions panel: where you record your code, used to define variables and functions
Interactions panel (read-eval-print loop): is for experimenting with expressions

binary search, cutting the number of possibilities in half at each step

keyword: e.g. define

set! = set bang

____________________________________________________________________

Syntax = grammar, the collection of rules that a phrase must follow to qualify as a valid sentence.
Semantics = meaning, 
Syntax error = improper code formation

function - element - element - element - element

Simple syntax is a defining characteristic of the Lisp family of languages.

reader: part of a compiler or interpreter

brackets are often used to group conditionals
parentheses are used for function applications

code alone will not make Racketeers happy, code with comments on the other hand...

line comment, indicated by ; 
    wherever Racket sees a semicolorn, it considers the rest of the line a comment.
block comment, indicated by #| at the start, |# at the end
    useful for large blocks of commentary
s-expression comment, indicated with #;
    it tells Racket to ignore the next parenthesized epression
    
    
pieces of data are the basic building blocks of meaning

Data types:
Booleans, binary, answers to yes/no questions
Symbols, case sensitive
Numbers, floating-point numbers, integers, rationals, complex numbers
Strings, because humans communicate with text

string-append

Help Desk, move your cursor over a name and press F1

Lists in Racket

CONS cells
  fxns for cons cell
  raw cons cell
  
car cell
cdr cell

manipulating lists in Racket, three basic functions
  empty
  '()
  (list)
  
  CONS Function
    using cons = consing
    
  FIRST
  
  REST
    
  LIST Function
  
  Nested Lists
  
 Functions for accessing the first through tenth elements are built in.
 
 
 Structures in Racket
 
 Structure definition: struct
 
 instance
 fields
 accessors
 
 field selectors, selectors
 
 structure transparency  #:transparent
 
 nesting structures


