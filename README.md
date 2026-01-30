\# Analisi delle vulnerabilità di libpng tramite AFL Fuzzing



Questa repository contiene il materiale relativo alla mia tesi di laurea riguardante l'uso di \*\*American Fuzzy Lop (AFL)\*\* per l'identificazione di bug nel parsing dei chunk di file PNG.



\## 📌 Descrizione del Progetto

Il lavoro si focalizza sulla libreria `libpng` e analizza in particolare come mutazioni specifiche nel chunk \*\*PLTE\*\* (palette) possano portare a crash del software o corruzione di memoria.



\## 📂 Struttura del Repository

\* `main.pdf`: La versione finale della tesi completa di indice e analisi tecnica.

\* `src/`: Codice sorgente LaTeX, immagini dei dump esadecimali e log di crash.



\## 🛠️ Strumenti Utilizzati

\* \*\*Benchmark\*\*: MAGMA

\* \*\*Fuzzer\*\*: AFL (American Fuzzy Lop)

\* \*\*Target\*\*: libpng

\* \*\*Debugger\*\*: GDB per la Root Cause Analysis dei crash identificati.



\## 🚀 Come compilare il documento

Per rigenerare il PDF dai sorgenti, è necessaria una distribuzione LaTeX (es. TeX Live o MiKTeX) ed eseguire:

```bash

pdflatex main.tex

pdflatex main.tex

