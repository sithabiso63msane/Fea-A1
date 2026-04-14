Finite Element Report Project
============================

Files:
- report.tex          Main LaTeX source
- references.bib      Bibliography file
- assets/             Figures, contours, and generated plots

Compile locally with:
1. pdflatex report.tex
2. bibtex report
3. pdflatex report.tex
4. pdflatex report.tex

Or with latexmk:
latexmk -pdf report.tex

Notes:
- Student name and student number are defined near the top of report.tex.
- The cover page uses a UJ-branded layout created directly in LaTeX.
- All reported numerical values are already populated from the uploaded result reports.
