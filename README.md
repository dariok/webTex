# webTex
A web service to pass LaTeX-files to XeLaTeX and return the result

Idea: POST a .tex or a .zip with several .tex to the server which will save them temporarily, run XeLaTeX 3-4 times, generate an index, run XeLaTeX and return the result.
Maybe as a Tomcat service?
