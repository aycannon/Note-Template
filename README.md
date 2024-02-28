# Note-Template
LaTeX note template catered to economics students who use STATA. Gives the ability to create textbook-looking notes and write STATA source code in LaTeX.

Almost all features of the template are completely customisable: contents page, tcolorbox, listings etc. 

For those who do not know how to compile TeX files:
- Download the zip file in the "code" dropdown (this should give you three files: main.tex, preamble.tex, README.md)
- The two tex files are important
- go to overleaf (or other LaTeX compiler) and add all of these files to a project
- then click recompile and everything should work.

if there are issues caused by having two files, you can copy and paste all the contents of the preamble into the main tex file (before the begin document command) and remove the input{preamble} command.

The bulk of the STATA formatting is from https://github.com/satejsoman/stata-lstlisting

