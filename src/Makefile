TEX = pdfcsplain
OUTPUT_DIR = ../build
TEXFLAGS = -output-directory=$(OUTPUT_DIR)

all: bakalarska-prace.tex
	mkdir -p $(OUTPUT_DIR)
	$(TEX) $(TEXFLAGS) bakalarska-prace.tex
	$(TEX) $(TEXFLAGS) bakalarska-prace.tex
	$(TEX) $(TEXFLAGS) bakalarska-prace.tex

.PHONY: clean

clean:
	rm $(OUTPUT_DIR)/*.log
