---
title: "Mit KITAplus einen Schritt Richtung Inklusion"
titlepage-logo: "files/HFHLogo.svg"
subtitle:
  - "Eine quantitative Studie zur Fremdbetreuung von Kindern mit sonderpädagogischem Förderbedarf im KITAplus-Programm"
title-logo: files/HFHLogo.svg
title-picture:

thesis-where:
  - "Masterarbeit im Studiengang Sonderpädagogik"
  - "mit Vertiefungsrichtung Heilpädagogische Früherziehung"
handed-in-by: "eingereicht von"
author: "I. N."
on-date: "im"
date: "Juni 2022"
recommended-by:
    - "Begleitung: M. L."
location: "Luzern, 2022"

bibliography: "literature/bibliography.bib"
csl: "literature/deutsche-gesellschaft-fur-psychologie.csl"
link-citations: true
crossrefYaml: "includes/pandoc-crossref.yaml"

acknowledgement-title: Danksagung

fontsize: 11pt
lang: de-DE

toc: true
lot: false
lof: false
pandoc-latex-unlisted: [unlisted]
toc-depth: 2
top-level-division: chapter
secnumdepth: 3
---

<!-- Table adjustments -->
:::{include-if-format=latex;native;json}
\newcommand{\adjustTableFormat}{
\begingroup\singlespacing\fontsize{10pt}{11pt}\selectfont\setlength{\LTpre}{0pt}\setlength{\LTpost}{6pt}
}
\newcommand{\adjustTableFormatEnd}{
\endgroup
}
:::

```{.include}
chapters/Abstract.md
chapters/Danksagung.md
chapters/Einleitung.md
chapters/Grundlagen.md
chapters/ForschungsmethodischesVorgehen.md
chapters/EvaluationUndDiskussion.md
chapters/Ausblick.md
chapters/Literaturverzeichnis.md
chapters/Abbildungsverzeichnis.md
chapters/Tabellenverzeichnis.md
chapters/Anhang.md
```
