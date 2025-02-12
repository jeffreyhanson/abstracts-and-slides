all: slides.html

clean:
	rm -rf slides.html

slides.html: slides.Rmd libs/* styles.css
	R -e "rmarkdown::render('slides.Rmd')"

.PHONY: all clean
