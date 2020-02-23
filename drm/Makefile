.PHONY: all
all: slides.pdf README.md

SRC=		slides.tex abstract.tex preamble.tex bibliography.bib
SRC+= 		contents.tex

DEPENDS= 	beamer-didactic.sty

slides.pdf: ${SRC}


TEX2MDFLAGS= 	-s --bibliography bibliography.bib -t markdown_strict

README.md: video.md abstract.md
	${CAT} video.md > $@
	${CAT} abstract.md >> $@

.INTERMEDIATE: abstract.md

abstract.md: abstract.tex
	${CONVERT.tex.md}


.PHONY: clean
clean:
	${RM} slides.pdf
	${RM} abstract.md


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
include ${INCLUDE_MAKEFILES}/doc.mk
INCLUDE_BEAMERDIDACTIC=../beamer-didactic
include ${INCLUDE_BEAMERDIDACTIC}/beamer-didactic.mk
