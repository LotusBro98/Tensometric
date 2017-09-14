SOURCE=documentation.tex
TARGET=documentation.pdf

all: open

$(TARGET): $(SOURCE)
	xelatex $(SOURCE)

open: $(TARGET)
	evince $(TARGET)
