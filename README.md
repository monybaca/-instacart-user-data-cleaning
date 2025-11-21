# Instacart User Data Cleaning

Este proyecto se enfoca en la limpieza, estandarización y preparación de los datos de usuarios de Instacart. Incluye la validación del identificador de usuario (`user_id`), la normalización de las listas de categorías favoritas y la creación de funciones reutilizables para preprocesar la información antes de realizar análisis más profundos.

## 📌 Objetivo
Garantizar que los datos relacionados con usuarios estén en un formato consistente y listo para análisis posteriores. Para lograrlo, este proyecto contempla:

- Validación de la estructura del `user_id`.
- Conversión de listas de categorías favoritas a formato uniforme (minúsculas y sin inconsistencias).
- Limpieza de espacios, caracteres especiales y formatos irregulares.
- Creación de funciones modulares (`clean_user`, `clean_users_batch`) para automatizar el preprocesamiento.
- Generación de un dataset final con usuarios completamente estandarizados.

## 🧹 Proceso de Limpieza
- Implementación de una función para limpiar un usuario individual.
- Normalización de valores en la columna `favorite_categories`.
- Iteración por listas de usuarios para generar versiones limpias.
- Ensamble de una lista final de usuarios estructurados y listos para análisis.
- Visualización del resultado de forma clara para verificar la calidad del preprocesado.

## 🛠 Tecnologías Utilizadas
- **Python**
- **Pandas**
- **Jupyter Notebook**

## 📁 Archivos del Proyecto
- `instacart-user-data-cleaning.ipynb` — Notebook principal con el proceso completo.
- (Opcional) Carpeta `data/` si deseas agregar datos de ejemplo.
- (Opcional) Carpeta `images/` si deseas incluir capturas o diagramas.

## 📈 Resultados
El proyecto deja preparado un dataset limpio de usuarios, apto para análisis de gasto, segmentación, recorridos de cliente o creación de modelos de recomendación en proyectos posteriores.
