# Plantilla-CLIC
----
Plantilla LaTeX para la Revista Conocimiento y Licenciamiento Libre


## Estructura de la plantilla base (clic.tex)

```latex
\documentclass[12pt,letterpaper]{book}
\usepackage{cliccenditel}

\nrorevista{X}
\anorevista{Y}
\autortapa{Fulano}
\autoresimg{Mengano,Zutano}
\maquetadores{Fulano, Mengano, Perengano, Perencejo}
\autorpresentacion{Perengano}
\autoreditorial{Perencejo\\Comité Editorial}

\begin{document}

\hojaportada
\hojalicencia
\input{comite}
\tablacontenido
\hojapresentacion
\hojaeditorial
\mainmatter
\fancychapterstyle

\chapter{Artículos sobre creación del conocimiento}\BgThispage
\input{art1}

\chapter{Experiencias de Conocimiento Libre}\BgThispage
\input{art1}

\chapter{Reseñas}\BgThispage
\input{art1}

\chapter{Boletines}\BgThispage
\input{art1}

\hojacontraportada
\end{document}
```
## Ejemplos

### Vista previa.
![thumbnail.png](thumbnail.png "Vista previa")

### Revista Conocimiento y Licenciamiento Libre N°13.
![demo.png](demo.png "Vista previa")





