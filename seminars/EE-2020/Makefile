all: abstract.docx

clean:
	rm -f abstract.docx

abstract.docx: README.md
	pandoc -f markdown+superscript -s -o abstract.docx README.md
