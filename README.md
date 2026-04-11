## AIOps en prevención de incidentes en canales de pago

Autores: Jaime Alberto Sierra Sierra, Juan Carlos Parra Martínez  
Programa: Maestría en Inteligencia Artificial  
Institución: Universidad de Especialidades Espíritu Santo (UEES)  
Asignatura / Proyecto: Proyecto integrador de inteligencia artificial  
Fecha: abril de 2026  

## Resumen

Este repositorio documenta las fases de preparación, procesamiento y adecuación de datos para el proyecto integrador dentro del dominio y problema elegido: desarrollo de un sistema de AIOps para la prevención y diagnóstico de incidentes en canales de pago. El trabajo se centra en la construcción de un pipeline reproducible de datos, partiendo de telemetría cruda de microservicios de alta concurrencia, con el objetivo de dejar un dataset final limpio, balanceado, enriquecido y listo para entrenamiento en modelos de aprendizaje automático y arquitecturas basadas en Transformers (BERT).

Componentes del proyecto:

- Análisis exploratorio de datos (EDA),
- Limpieza y validación de calidad,
- Feature engineering,
- Balanceamiento de clases,
- Data augmentation mediante fault injection,
- Anonimización y preprocesamiento automatizado.
- Pendientes nuevos procesos...

## Contexto del problema

En ecosistemas transaccionales modernos, como pasarelas de pago y sistemas de facturación, la continuidad operativa depende de la capacidad de detectar tempranamente fallos, degradaciones del servicio y anomalías en tiempo real. La arquitectura de microservicios genera grandes volúmenes de telemetría y logs que superan la capacidad de análisis manual.

En este contexto, la preparación adecuada de los datos es crítica para entrenar modelos de inteligencia artificial capaces de anticipar incidentes operativos, identificar patrones de degradación, apoyar análisis de causa raíz (Root Cause analysis, RCA) y mejorar las capacidades del sistema.
 

## Dataset de referencia

El análisis se fundamenta en un conjunto de datos de telemetría de microservicios obtenido desde Kaggle, correspondiente a eventos operativos y transaccionales en un entorno simulado de alta concurrencia.

### Características generales del dataset

- Volumen inicial: más de 426,000 registros
- Tipo de datos:
  - variables numéricas continuas,
  - variables categóricas,
  - texto no estructurado asociado a logs y eventos
- Dominio de aplicación: observabilidad, AIOps y prevención de incidentes
- Clase dominante: tráfico exitoso (`HTTP 200`)
- Problema principal detectado: desbalance extremo de clases

## Metodología implementada

1. Análisis Exploratorio de Datos (EDA)
2. Limpieza de datos
3. Feature Engineering
4. Balanceamiento de clases
5. Data Augmentation
6. Preprocesamiento automatizado
7. Anonimización y privacidad
Producto final
