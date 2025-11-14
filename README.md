# Actividad 1- Anlisis de Secuencias de Cancer de Pulmón

Este proyecto consiste en el análisis bioinformático de secuencias genéticas asociadas al cáncer de pulmón con el objetivo de identificar variaciones, regiones conservadas y características relevantes desde el punto de vista molecular.
Realizando un análisis bioinformático de datos de RNA-Seq del adenocarcinoma de pulmón utilizando datos públicos de TCGA (The Cancer Genome Atlas). El objetivo es identificar genes diferencialmente expresados entre tejido tumoral y normal, validando hallazgos reportados en la literatura científica

## Objetivo general:

Analizar secuencias asociadas al cáncer de pulmón para identificar patrones, variaciones y características relevantes que permitan comprender mejor su comportamiento molecular.

## Objetivos especificos:

- Identificar genes significativamente sobreexpresados y reprimidos en adenocarcinoma pulmonar
- Realizar análisis de enriquecimiento funcional de pathways biológicos
- Validar los hallazgos del estudio seminal de TCGA (Nature 2014)
- Crear un flujo de trabajo reproducible de análisis de RNA-Seq

## Estructura del repositorio

El repositorio está organizado en cuatro carpetas principales, cada una con un propósito específico dentro del análisis bioinformático de las secuencias de cáncer de pulmón:

1. Data/: contiene todos los archivos de datos utilizados en el proyecto. Dentro de esta carpeta se encuentran los datos originales (por ejemplo, secuencias en formato FASTA) y los datos procesados que se generan durante el análisis.
Este proyecto utiliza datos simulados basados en el perfil de adenocarcinoma pulmonar de TCGA. Los archivos incluyen:

- `sample_metadata.csv`: Información de muestras y pacientes
- `gene_counts_sample.csv`: Matriz de expresión génica simulada
- `differential_expression_results.csv`: Resultados de análisis DE simulados
- `experimental_design.csv`: Diseño experimental simulado

3. Script/: incluye los scripts utilizados para realizar el procesamiento y análisis de las secuencias. Aquí se almacenan los archivos en R, Python u otros lenguajes que implementan los pasos principales del flujo de trabajo.

4. Notebook/: agrupa los notebooks desarrollados para exploración, análisis interactivo y visualización. Estos pueden ser archivos RMarkdown o Jupyter Notebook donde se documenta y ejecuta el análisis de manera más detallada.

5. Results/: almacena los resultados generados a partir del análisis, como gráficos, tablas, reportes o cualquier archivo producido por los scripts o notebooks. Esta carpeta permite visualizar fácilmente los hallazgos del proyecto.

## Resultados Esperados
- Lista de genes diferencialmente expresados
- Análisis bioinformatico de genes
- Visualizaciones: Volcano plots, heatmaps, diagramas de enriquecimiento

## 👥 Contribuyentes
- Luisa Michel Riascos Garcia
- Dariem Hernandez Díaz
- Valentina Naecáez Gaitán 

## 📚 Referencias
- [TCGA Lung Adenocarcinoma Study - Nature 2014](https://www.nature.com/articles/nature11404)
- [TCGAbiolinks Documentation](https://bioconductor.org/packages/release/bioc/html/TCGAbiolinks.html)
