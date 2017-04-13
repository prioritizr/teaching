all: clean build

build:
	R -e "rmarkdown::render('slides.Rmd')"

clean:
	rm -rf slides.html


.PHONY: all clean build
