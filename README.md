pandoc -s -B remerciements.txt resume.txt introduction.txt chapitre-I.txt chapitre-II.txt chapitre-III.txt chapitre-IV.txt conclusion.txt bibliographie.txt pdf.yaml --pdf-engine=xelatex --template=pdf-template.latex -o memoire-ajuste.pdf

Nécessite plusieurs paquets TeX à installer avec `sudo tlmgr`.
