# Makefile for Landslide

# You can set these variables from the command line.
SBIN = landslide

.PHONY: help html pdf

help:
	@echo "Please use \`make <target>' where <target> is one of"
	@echo "  html    to make standalone HTML files"
	@echo "  pdf     to make standalone PDF file"

clean:
	-rm presentation.html

html:
	$(SBIN) config.cfg
	@echo
	@echo "Build finished."

pdf:
	$(SBIN) config.cfg -d readme.pdf
	@echo
	@echo "Build finished."
