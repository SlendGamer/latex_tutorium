# LaTeX-Tutorium

Dieses Tutorium dient zur Vorbereitung auf die ersten Arbeiten bzw. auf die Bachelor- oder Masterarbeit.

- Aktuelle Versionen: [MiKTeX](https://miktex.org/download), [Texmaker](https://www.xm1math.net/texmaker/download.html)
- Online-Editor [Overleaf](https://www.overleaf.com/)

Änderungen vorbehalten.

## Skript

Die PDF für das Skript liegt im Unterordner `LaTeX_Skript/build`.

## Übungsaufgaben

Die PDF für die Übungsaufgaben liegt im Unterordner `LaTeX_Übungen/build`.

## Hilfsmittel

Ich habe im Ordner `cheat-sheets` ein paar Cheat-Sheets hinterlegt, allerdings ist mir im Laufe der Arbeit mit LaTeX aufgefallen, dass es besser ist, die Online-Varianten zu benutzen:

- [GoLaTeX](https://golatex.de/wiki/index.php/Hauptseite): Deutsches LaTeX-Wiki
- [LaTeX-Wikibooks](https://en.wikibooks.org/wiki/LaTeX): LaTeX-Wiki mit Anwendungsbeispielen zu fast allen Paketen und Befehlen
- [Detexify](https://detexify.kirelabs.org/classify.html): Finden von Symbolen durch Zeichnen
- [LaTeX-Cheat-Sheet](http://wch.github.io/latexsheet/)
- [LaTeX Einführung](https://tobi.oetiker.ch/lshort/lshort.pdf) (lang)

# Texmaker-Kurzeinführung

Wenn man Texmaker frisch installiert hat ist es sinnvoll sich zunächst damit vertraut zu machen. Ich arbeite mich von **Oben nach Unten** und von **Links nach Rechts**

#### Datei

Ganz links im Reiter `Datei` findet man bekannte Befehle, um Dokumente abzuspeichern. Ein wichtiger Punkt ist jedoch die **Sitzung**.

Eine Sitzung speichert, welche Dateien zum Zeitpunkt des Speicherns geöffnet waren und welche Datei dabei die **Masterdatei** war. Beim nächsten Öffnen muss dann lediglich die Sitzung wieder geöffnet werden.

Wo wir gerade dabei sind: Eine **Masterdatei** kann über den Reiter `Optionen` festgelegt werden. Sie zeigt LaTeX, welche Datei überhaupt **kompiliert** werden soll, denn kompilierfähig ist **nur** die Datei mit den Strukturelementen:

`\documentclass{...} \begin{document} ... \end{document}`

#### Bearbeiten

Hier sind Befehle, die man fast aus jedem Programm kennt. Wirklich Besonderes gibt es hier nicht, jedoch die **Kommentar / -entfernen** und **Einrücken / Ausrücken** Funktion ist ganz nützlich.

#### Werkzeuge

LaTeX ist nicht gleich LaTeX! Im Laufe der Jahre haben sich verschiedene Zweige entwickelt, die eine gesonderte Funktion haben. Im Reiter `Werkzeuge` findet man die Shortcuts zum Aufruf dieser.

So ist beispielsweise `PDFLaTeX` zum übersetzen des LaTeX-Dokuments in eine für eigentlich alle Geräte bekannte `pdf-Datei` möglich.

Hier eine kleine Aufzählung, was die wichtigsten Dienstprogramme machen:

- `Schnelles Übersetzen`: Voreingestellte Kombination aus einem oder mehreren Befehlen
- `PDFLaTeX`: Übersetzung in PDF
- `BibTeX`: Erstellung Literaturverzeichnis (muss ggf. mehrmals nacheinander durchlaufen)
- `MakeIndex`: Erzeugung/Aktualisierung des Index- und Abkürzungsverzeichnisses

#### LaTeX

#### Formel

#### Assistenten

Nach dem ersten Starten wird ein überwiegend leeres Fenster angezeigt. Um eine LaTeX-Datei zu erstellen kann man dies natürlich über den Explorer durch Anlegen einer `.tex-Datei` machen, aber die Benutzeroberfläche von Texmaker bietet einige sog. **Assistenten**, die dies vereinfachen:

- Assistent für ein neues Dokument,
- schnelle Beamer Präsentation,
- Brief-Assistent, usw.

Für den Inhalt gibt es folgende weitere Assistenten:

- Tabellen-,
- Tabulator- und
- Matrix-Assistent

#### Bibliographie

#### Benutzer/in

#### Ansicht

#### Knöpfe zum Kompilieren

## Empfohlene Einstellungen
