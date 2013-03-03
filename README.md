# Truth Tables Generator for LaTeX

This is a simple truth table generator that parses a text expression and outputs a LaTeX truth table for your expression.

## Usage 

This generator is JavaScript powered. You will need the [NodeJS](http://nodejs.org/) runtime to use it.

Example : 
<pre>
./truth.js "(p v ( q xor not r)) xor not (( p -> r) ->q)" > example.tex
</pre>

Make sure you include the array package and that you don't redefine the column type twice.
