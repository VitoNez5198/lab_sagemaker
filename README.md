# AWS SageMaker — Laboratorios de Machine Learning

[![Amazon SageMaker](https://img.shields.io/badge/AWS-Amazon%20SageMaker-FF9900?logo=amazon-aws&logoColor=white)](https://aws.amazon.com/sagemaker/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-ML-blue?logo=python)](https://www.python.org/)

> Colección de notebooks y datasets de práctica desarrollados sobre **Amazon SageMaker** para clasificación supervisada y exploración de datos en Python.

---

## Contexto y Alcance

Este repositorio agrupa laboratorios prácticos orientados al ciclo básico de Machine Learning en AWS: carga y preparación de datasets (`ARFF` / `.dat`), entrenamiento de modelos de clasificación (binaria `2C` y multiclase `3C` sobre el dataset de columna vertebral) y evaluación en notebooks de **Amazon SageMaker**.

---

## Contenido del Repositorio

| Archivo | Descripción |
| :--- | :--- |
| [3_4-machinelearning.ipynb](3_4-machinelearning.ipynb) | Flujo de clasificación supervisada en SageMaker usando el dataset `column_2C` / `column_3C`. |
| [lab/IA_aws.ipynb](lab/IA_aws.ipynb) | Notebook práctico de introducción a IA y ML en AWS. |
| [PythonCheatSheet.ipynb](PythonCheatSheet.ipynb) | Referencia rápida de estructuras y utilidades de Python para ciencia de datos. |
| `column_2C.*` / `column_3C.*` | Datasets de clasificación ortopédica (formatos `.dat` y Weka `.arff`). |

---

## FinOps y Buenas Prácticas en SageMaker

- **Apagado de Notebook Instances:** detener o eliminar instancias de SageMaker al finalizar cada sesión evita cobros continuos por hora de cómputo.
- **Endpoints:** eliminar endpoints de inferencia una vez concluidas las pruebas de predicción en tiempo real.

---

## Autor

**Víctor Martínez** — Junior Cloud Engineer | AWS, FinOps & Applied AI  
AWS Certified Cloud Practitioner • AWS Cloud re/Start • En preparación para SAA-C03

- **Portafolio:** [vitonez5198.github.io/Portfolio-VM](https://vitonez5198.github.io/Portfolio-VM/)
- **LinkedIn:** [victor-ms-dev](https://www.linkedin.com/in/victor-ms-dev/)
- **GitHub:** [@VitoNez5198](https://github.com/VitoNez5198)
