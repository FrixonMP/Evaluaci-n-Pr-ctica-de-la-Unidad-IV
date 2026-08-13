# Evaluación Práctica de la Unidad IV
# Prueba Práctica - Unidad IV (ISR-401)

**Estudiante:** Frixon Morán  
**Carrera:** Ingeniería de Software  
**Asignatura:** Ingeniería de Requisitos (ISR-401) - Paralelo B  
**Docente:** Ing. Gleiston Guerrero, Mg.  

---

## 🛠️ Instrucciones Exactas de Compilación

Para reproducir el archivo PDF a partir del código fuente LaTeX, sigue estas especificaciones:

* **Archivo principal:** `main.tex`
* **Compilador requerido:** `pdflatex` (junto con `bibtex` para las referencias).
* **Dependencias / Paquetes:** `graphicx`, `xcolor`, `tabularx`, `tcolorbox`, `hyperref`, `natbib`, `tikz`.

### Orden de Comandos para Compilación Local:

Si utilizas una terminal local con TeX Live o MiKTeX:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
