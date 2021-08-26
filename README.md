# Burmese---Latex

Required Packages: 
1. newunicodechar
2. fontspec

Define new environment with “Myanmar Text”.

To use environoment, use the lines “$\textnormal{\begin{bur} မက (insert Burmese letters here) \end{bur}}$”.  This works in text, equations and tables.

Important: 
Use the line ‘%!TEX TS-program = xelatex’ at the top of the document.  Without it, you might get an error that says “The fontsec package requires either XeTex or …”.
