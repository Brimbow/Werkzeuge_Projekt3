# LaTeX-Unterlagen

"In diesem Repository befinden sich die LaTeX-Unterlagen zum Modul."

## Inhalt

Der Inhalt entspricht dem Text der Aufgabe 2 des Moduls.

Es kann sinnvoll sein, sich die PDF zur Aufgabe 2 noch einmal anzusehen

## PDF erstellen

Das geht ganz schnell und einfach:

- Zuerst installieren wir LaTeX ([Tex Live](https://tug.org/texlive/))
- Dann nutzen wir PDFLaTeX zum Erstellen des PDF "pdflatex ./task.tex" (Das müssen wir mehrfach machen, damit die PDF auch fertig wird.)
- Alternativ können wir auch einfach LaTeX Mk nutzen "latexmk -pdf ./task.tex"

**!!ACHTUNG!!**
LaTeX erstellt einige nervige Dateien (.aux, .log) diese muss man löschen, bevor man einen Commit mit seinen Änderungen macht!

Mache zuerst NUR Aufgabe 1.1.2
