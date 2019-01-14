
all: CommissionCDF2018.pdf

%.pdf: %.tex
	pdflatex $^
	#Twice for ToC
	pdflatex $^

clean:
	rm -rf *.aux *.out *.log *.pdf
