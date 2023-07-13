# Tiny-Compiler
Compiler for a Tiny programming language by using c#
Fully implemented Scanner and Parser for Tiny Compiler
Features
A program in TINY consists of a set of functions (any number of functions and ends with a main function).

Each function is a sequence of statements including (declaration, assignment, write, read, if, repeat, function, comment, …).

Each statement consists of (number, string, identifier, expression, condition, …).

Usage/Examples
/* Sample program in Tiny language – computes factorial*/

int main()
{

int x;
read x;     /*input an integer*/
if x > 0 then     
  int fact := 1;
  repeat
      fact := fact * x;
      x := x – 1;
  until x = 0
  write fact; /*output factorial of x*/
end
return 0;
}
