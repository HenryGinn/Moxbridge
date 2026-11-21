SOURCES = MoxbridgePreviouslySeenQuestions-Light.tex MoxbridgePreviouslySeenQuestions-Dark.tex MoxbridgeQuestionsAndSolutions-Light.tex MoxbridgeQuestionsAndSolutions-Dark.tex
PDFS = $(SOURCES:.tex=.pdf)

.PHONY: all

all: $(PDFS)

%.pdf: %.tex
	latexmk $<

clean:
	latexmk -C

distclean: clean
	rm -f $(PDFS)

