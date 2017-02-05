
all: Charte_Commission.pdf

%.pdf: %.tex
	pdflatex $^
	#Twice for ToC
	pdflatex $^

clean:
	rm -rf *.aux *.out *.log *.pdf
