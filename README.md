# Useful Command Line Tools
A collection of useful command line tools and basic usage

## PDFtk - https://www.pdflabs.com/docs/pdftk-man-page/

Installing: sudo apt-get install pdftk 

Basic Usage:

1. Modifying PDF Metadata

pdftk Tour-Breakfast-Menu.pdf dump_data output Metadata-output.txt // create text document with meta info

vim Metadata-output.txt // modify Metadatt

sudo pdftk Tour-Breakfast-Menu.pdf update_info Metadata-output.txt output Tour-Breakfast-Menu-new.pdf // output changed file
