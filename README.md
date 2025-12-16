# ETL de Datos de Encuesta & Design Thinking – Experiencia del Paciente

## Contexto de Negocio

Los centros médicos privados suelen recopilar retroalimentación de sus pacientes a través de plataformas de encuestas como **SurveyMonkey**.

En este caso, un **centro médico privado de tamaño mediano** ofrece un servicio médico de alta calidad; sin embargo, los pacientes reportan una fuerte **insatisfacción con la experiencia administrativa antes y después de la cita**. Entre los principales problemas se identifican largos tiempos de espera, procesos poco claros, falta de comunicación y ausencia de recordatorios automáticos, lo que impacta negativamente en la **satisfacción del cliente y el NPS**.

Este proyecto aborda el problema combinando **Design Thinking** con **análisis de datos y un proceso ETL**, permitiendo comprender, medir y rediseñar la experiencia del paciente.
---
## Objetivo

Simular la extracción de datos de encuestas de pacientes desde una **API REST (SurveyMonkey)** y transformarlos en un **dataset listo para análisis**, aplicando principios de Design Thinking para:

* Comprender las necesidades y emociones de los pacientes
* Identificar puntos de dolor en el proceso administrativo
* Medir satisfacción y NPS
* Facilitar la toma de decisiones basada en datos

---

##  Proceso ETL

### Extract (Extracción)

* Uso de un **JSON mock** que simula la respuesta de la API de SurveyMonkey


### Transform (Transformación)

* Normalización del JSON utilizando **Pandas**
* Limpieza y estandarización de campos para análisis
* Creación de métricas de negocio:

  * Clasificación NPS (Promotores, Pasivos, Detractores)
  * Satisfacción pre y post cita
  * Indicador de frustración administrativa

### Load (Carga)

* Exportación de un dataset limpio y estructurado en formato CSV
* Dataset optimizado para modelado y visualización en **Power BI**

---

## Herramientas

* Python
* Pandas
* JSON
* Google Colab / Jupyter Notebook
* Power BI
* Miro/Canvas

---

## Resultados

* Dataset limpio listo para análisis en BI
* KPIs disponibles para visualización:

  * NPS
  * Satisfacción (pre vs post cita)
  * Tiempo promedio de espera
  

---

## Aprendizajes

* Comprensión de estructuras reales de APIs de encuestas
* Técnicas de normalización y transformación de JSON
* Diseño de un pipeline ETL end-to-end
* Aplicación de Design Thinking apoyado en datos
* Traducción de insights cualitativos en métricas cuantitativas

---

--> Los datos utilizados en este proyecto son simulados y se emplean únicamente con fines académicos y de portafolio, replicando estructuras reales de la API de SurveyMonkey.

---

**Autora:** María Sophia Torres Conejo
Ingeniería en Producción Industrial · Business & Data Analytics
