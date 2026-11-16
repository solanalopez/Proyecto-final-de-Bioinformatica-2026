# Proyecto-final-de-Bioinformatica-2026
Clasificación de cinco tipos de cáncer mediante técnicas de bioinformática y machine learning
Este proyecto analiza datos de expresión génica de 801 muestras de pacientes, correspondientes a cinco tipos de cáncer: mama (BRCA), colon (COAD), riñón (KIRC), pulmón (LUAD) y próstata (PRAD).

Se utilizaron herramientas de bioinformática y aprendizaje automático, incluyendo PCA, K-Means, árboles de decisión, Random Forest, SVM y redes neuronales, para estudiar los patrones de expresión génica y clasificar las muestras.

Dataset

Fuente: UCI Machine Learning Repository — Gene Expression Cancer RNA-Seq.

Descarga: https://archive.ics.uci.edu/dataset/401/gene+expression+cancer+rna+seq

El dataset original contiene 801 muestras y 20.531 variables de expresión génica.

El archivo labels.csv se encuentra en este repositorio. Debido al tamaño de data.csv, se proporciona el enlace oficial para descargar los datos completos.

Resultados principales

Random Forest: 99,50 % de exactitud estimada mediante OOB.

SVM con kernel RBF: 98,14 % de exactitud en el conjunto de prueba.

Red neuronal: 98,14 % de exactitud en el conjunto de prueba.

Random Forest con selección de 10 genes: 96,89 % de exactitud en el conjunto de prueba.

Archivos

Notebook .ipynb: análisis completo realizado en Google Colab.

labels.csv: etiquetas de los tipos de cáncer.

data.csv: disponible para descarga desde el enlace oficial indicado anteriormente.

Limitaciones

Los genes se identifican mediante códigos como gene_9175, por lo que no se les asignan nombres biológicos sin una correspondencia verificada. Los resultados corresponden a un análisis académico y no constituyen una herramienta de diagnóstico clínico.
