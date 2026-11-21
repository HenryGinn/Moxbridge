all: Solutions SolutionsDark PreviouslySeen PreviouslySeenDark

Solutions:
	latexmk -f -pdf -jobname=MoxbridgeQuestionsAndSolutions-light \
	MoxbridgeQuestionsAndSolutions.tex

SolutionsDark:
	latexmk -f -pdf -jobname=MoxbridgeQuestionsAndSolutions-dark \
	-pdflatex="pdflatex %O \"\def\DarkMode{}\input{%S}\"" \
	MoxbridgeQuestionsAndSolutions.tex

PreviouslySeen:
	latexmk -f -pdf -jobname=MoxbridgePreviouslySeenQuestions-light \
	MoxbridgePreviouslySeenQuestions.tex

PreviouslySeenDark:
	latexmk -f -pdf -jobname=MoxbridgePreviouslySeenQuestions-dark \
	-pdflatex="pdflatex %O \"\def\DarkMode{}\input{%S}\"" \
	MoxbridgePreviouslySeenQuestions.tex