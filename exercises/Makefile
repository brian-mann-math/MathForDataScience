# Build lecture slides for time series

# Commands
PANDOC = pandoc --latex-engine=pdflatex
RM = rm -f

# Files
TGT = exercises.pdf

# Rules
default: $(TGT)

lecture: default

all: default

clean:
	$(RM) $(TGT)

%.pdf : %.md
	$(PANDOC) $< -o $@
