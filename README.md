# Pandoc workflow

This contains a Makefile and latex headers that allow me to quickly write 
homework assignments for math and CS, especially for submission to Crowdmark or 
any other service that requires separate submission per assignment question.

## Usage

Write each separate question as its own `{name}.md` file. Run `make` to generate 
a corresponding `{name}.pdf` for each markdown file. Run `make clean` to remove 
all generated pdf files.
