# PDF_PROGRAM

## This is a Step by step guide for installation and execution of the project

### SETUP ENVIRONMENT

1. Placed required files
- Create a folder in C: directory called pdfproject (C:\pdfproject). Inside this folder copy the next files:
  * test2.pdf
  * template.pdf
  ( You can find these files inside the project)
- Save the app.py file in the pdfproject folder
- In this same folder create another folder called output (C:\pdfproject\output)


![image](https://github.com/JuPaRaMo/pdf_program/assets/30596170/ed70e798-0aaa-44c8-8be5-001ba747e858)

 2. Setup python project

 - The python version used for this project is 3.9.13.
 Go to the root of the project and install the next library
 ```python
 pip install PyPDF2
 ```
 
  At this point you are all set to run the app using the following command:
 ```python
 python extract_pages.py test2.pdf template.pdf output/output.pdf
 ```


