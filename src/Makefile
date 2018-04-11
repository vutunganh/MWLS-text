TEX = xelatex
OUTPUT_DIR = ../build
TEXFLAGS = -output-directory=$(OUTPUT_DIR)

all: bakalarska-prace.tex
	mkdir -p $(OUTPUT_DIR)
	$(TEX) $(TEXFLAGS) $^
	biber $(OUTPUT_DIR)/bakalarska-prace.bcf
	$(TEX) $(TEXFLAGS) $^
	$(TEX) $(TEXFLAGS) $^

.PHONY: clean

clean:
	cd $(OUTPUT_DIR) && rm *.log *.aux *.bbl *.blg *.ref *.lof *.out *.toc
