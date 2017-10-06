
ALLFILES = README Makefile lingmacros.sty tree-dvips.sty avm.sty tree-dvips91.pro \
      tree-dvips91.script tree-manual.tex lingmacros-manual.tex avm-doc.tex \
      avm-doc.sty

all: tree-dvips.pro 

tar: 
	tar cf tree-dvips.tar ${ALLFILES}

tree-dvips.pro: tree-dvips.script
	squeeze < tree-dvips.script > tree-dvips.pro
