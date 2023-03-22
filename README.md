# NLP-Extracting-Text-from-PDF

This repository contains 3 different ways to extract text from a PDF file.

1. With PyPDF2 package 
  this is a Python based package. It did not have any issue with installing and/or importing. The whole file MUST be stored in a single variable (see: res) and then word tokenized to get words.
  
2. With Tika package
  This is a java based package. So java must be installed in the machine. Otherwise, this is same as PyPDF2
  
3. With OCR:
  This comes in handy if the PDF is scanned OR there is some encoding involved. Installing might take some time and troubleshooting. The way this works: it converts every page of PDF to a seperate image file and store it. Then it reads the images with tesseract OCR and identifies the text.
