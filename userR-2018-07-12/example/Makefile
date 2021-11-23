all: article

article: article/article.html

article/article.html: code/article.Rmd
	R -e "rmarkdown::render('code/article.Rmd')"
	mv code/article.html article/

clean:
	@rm -f article/article.pdf
	@rm -f article/article.html

.PHONY: article clean
