TEXSTYLES=./tree-dvips/lingmacros.sty:./tree-dvips/tree-dvips.sty

resume: grammar.tex
	TEXFORMATS=$(TEXSTYLES) latex grammar.tex; 
	TEXFORMATS=$(TEXSTYLES) pdflatex grammar.tex;

