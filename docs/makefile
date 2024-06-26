HTML=index.html
PANDOC_HTMLOPT=--mathjax -t html --shift-heading-level-by=-1 --template=template 
TARGET=$(HTML)

all: $(HTML)

index.html: index.md
	pandoc -s $< -o $@ $(PANDOC_HTMLOPT)

clean:
	rm -f $(TARGET) index.html
