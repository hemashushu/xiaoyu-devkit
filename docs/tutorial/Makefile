SOURCE_DOCS := $(wildcard *.md)
EXPORTED_DOCS=\
	      $(SOURCE_DOCS:.md=.html)

%.html: %.md
	pandoc $< -f markdown -t html -s -o $@

all: $(EXPORTED_DOCS)
