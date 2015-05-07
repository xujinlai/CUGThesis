# CUGThesis
The \Latex Template for the Master Degree Graduate Thesis writing in China University of Geosciences.

This is a \Latex Template for Thesis Writing by Seeksky@CUG. Welcome to my homepage http://jinlaixu.net .
The Template is modified from the universal thesis template in USTC. Thanks very much for their effort in the template.  

# Intro
Please use \Xelatex for compiling the files. Maybe TexLive is better for the template, because I didn't test the availability when using MikTex.

Needed Files:
 * cugthesis.cls: all in one style class.
 * cugbib.bst: style for \Bibtex.
 * main.tex: the main file of the thesis with some examples of it.
 * clean.bat/sh: clean bash.
 * make.bat/sh: make bash.
 * /chapter: with all the subsection files in it including the abstract and so on.
 * /bib: just \Bibtex files for references.
 * /figures: the directory for figures. Please use PDF, EPS ans so on.
 
#Recommendation
I recommend **Sublime Text 3** + **LatexTool** + **TexLive** + **SumatraPDF** tool-chains.
Because after the configuration, you can compile the whole files with only needing to click **"Ctrl+B"**.
 
# Update Log
[20150507] v0.1.2
Modify some details to satisfy the requirements of CUG master dissertations.
The modification is below:
1.delete the Roman page number in the front matter.
2.modify the details in the cover page and the statement pages.
3.add the miss empty page after the first statement page.
4.fix the font size of tables and figures.
5.fix the main matter font size from cs4size to cs5size 

[20150316] v0.1.1
Change the sub-chapter files to UTF-8 without BOM.
Add the top flag to support the LatexTool for the mutil-files compiling and searching in Sublime Text 3.

[2016/03/06] v0.1
Create the template 