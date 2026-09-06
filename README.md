# VIS

Repositorio de la asignatura **Visualización (VIS)** — materiales de teoría, prácticas y Trabajo Académico.

## 👤 Autor

- **Osy** — estudiante de la asignatura

## 📖 Descripción

Este repositorio recoge los apuntes, enunciados, datasets y soluciones de las prácticas de la asignatura, organizados por bloques temáticos. Incluye ejercicios resueltos en **R** y **Python**, dashboards de **Tableau**, y el material de apoyo para el Trabajo Académico final.

## 🗂️ Estructura del repositorio

```
VIS/
├── CALENDARIO-VIZ_26-27.pdf                    # Calendario del curso 2026-27
├── Presentación.pdf                            # Presentación introductoria de la asignatura
├── Trabajo_académico.pdf                       # Enunciado del Trabajo Académico
│
├── Bloque_2._Estadística_y_Visualización/
│   ├── 1._Estadística_y_Visualización.pdf      # Teoría del bloque
│   ├── Práctica_1/                             # Enunciado + dataset "Contaminación en UPV 2015"
│   └── Seminario_Prácticas_Tableau/            # Ejemplo Global Superstore, guía de Tableau y dashboards
│
├── Bloque_3._Visualización_de_datos/
│   ├── Tema_1.pdf … Tema_4.pdf                 # Teoría del bloque
│   ├── ggplot2-cheatsheet.pdf / plotly_cheat_sheet.pdf
│   ├── Plotly/
│   │   └── Practica1 … Practica6/              # Enunciado + solución en R (.Rmd) y Python (.ipynb) + gráficos exportados en HTML
│   ├── ggplot/
│   │   └── Ejercicio_1 … Ejercicio_5/          # Enunciado, datasets y soluciones en R y Python (incluye datos geoespaciales)
│   └── spatialggplot-1.zip
│
└── Trabajo_académico/
    ├── Tablas_ejemplo/                         # Datasets de ejemplo (COVID-19, esperanza de vida, energía fósil, ventas PC)
    └── ejemplos_TA_curso_2020-21_videos/       # Vídeos de trabajos académicos de cursos anteriores
```

> Nota: en el repositorio real, las carpetas usan `_` en lugar de vocales acentuadas (p. ej. `Bloque_2._Estad_stica_y_Visualizaci_n`), probablemente por una sincronización previa con un servicio que no admite tildes en los nombres de archivo.

## 🛠️ Tecnologías y herramientas

| Herramienta | Uso |
|---|---|
| **R** (R Markdown `.Rmd`, notebooks `.nb.html`) | Soluciones de prácticas con `ggplot2` |
| **Python** (Jupyter `.ipynb`) | Soluciones de prácticas con `Plotly` y `ggplot` |
| **Tableau** | Dashboards del seminario del Bloque 2 |

## 📚 Contenido por bloque

### Bloque 2 · Estadística y Visualización
- Teoría de estadística aplicada a la visualización.
- Práctica 1: análisis de la contaminación en la UPV (2015).
- Seminario de Tableau: construcción de dashboards con el dataset *Global Superstore*.

### Bloque 3 · Visualización de datos
- Teoría (Temas 1-4).
- 6 prácticas con **Plotly** (Python y R), con los gráficos interactivos exportados en HTML.
- 5 ejercicios con **ggplot2** (R y Python), incluyendo visualización de datos geoespaciales con shapefiles.

### Trabajo Académico
- Datasets de ejemplo para el proyecto final: COVID-19, esperanza de vida, combustibles fósiles, ventas de PC.
- Vídeos de ejemplos de trabajos académicos de cursos anteriores (2020-21).

## ▶️ Cómo usar este repositorio

```bash
git clone https://github.com/Marioam200/VIS.git
```

- **Notebooks de Python** (`.ipynb`): ábrelos con Jupyter Notebook, JupyterLab o VS Code.
- **Archivos de R** (`.Rmd`): ábrelos en RStudio y usa *Knit* para generar el HTML con los resultados.
- **Gráficos exportados** (`.html`): se abren directamente en cualquier navegador.
- **Documentos de enunciados/teoría** (`.pdf`): visor de PDF habitual.

## 📄 Licencia

Material de uso académico y personal, elaborado como parte de la asignatura de Visualización.
