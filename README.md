# cv_fancy
Professional cv for a software engineer. Includes variables for English and Spanish language and the option to include a profile picture.

1. Download and install Latex.
2. Install your favourite Latex editor and open the file ‘cv.tex’
3. Generate a pdf document with your Latex editor or use ‘make’ in the command line.

The project allows to manage the following variable elements for your CV:

1. Languages: For instance, English (EN) or Spanish (ES)
2. Profile picture (picture)
3. Profile position: For instance, Systems engineer(SYS) or Software engineer (SOFT)
4. Sections: For instance, personal information, profile, experience, projects, education, languages, skills, references, certifications, courses and seminars.

To edit:

I have used texmaker, however any other editor should work.

To install:

It is necessary to use XeLatex:
"xelatex" -synctex=1 -interaction=nonstopmode %.tex
