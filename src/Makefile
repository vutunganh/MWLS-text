TEX = xelatex
OUTPUT_DIR = ../build
TEXFLAGS = -output-directory=$(OUTPUT_DIR)

all: bakalarska-prace.tex
	mkdir -p $(OUTPUT_DIR)
	$(TEX) $(TEXFLAGS) $^
	$(TEX) $(TEXFLAGS) $^

.PHONY: clean

clean:
	rm $(OUTPUT_DIR)/*.log $(OUTPUT_DIR)/*.aux $(OUTPUT_DIR)/*.bbl $(OUTPUT_DIR)/*.blg $(OUTPUT_DIR)/*.ref
