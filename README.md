# Evaluación y Mejora del Contexto en Large Language Models (LLMs)

## Objetivo

El objetivo principal de este trabajo es desarrollar un sistema de Generación Aumentada por Recuperación (Retrieval-Augmented Generation, RAG) que permita interactuar con la **Constitución Española**. Este sistema busca mejorar la precisión y relevancia en la generación de texto por modelos de lenguaje a gran escala (LLMs), integrando técnicas avanzadas de chunkerización y recuperación de información.

## Introducción

En los últimos años, los **Modelos de Lenguaje a Gran Escala (LLMs)** han revolucionado el procesamiento de lenguaje natural (NLP) gracias a su capacidad para generar texto coherente y relevante. Sin embargo, estos modelos enfrentan desafíos en la manipulación de información específica y detallada, lo que puede resultar en **alucinaciones** o en la generación de respuestas imprecisas.

Para abordar estos problemas, se propone el uso de **sistemas RAG**, los cuales combinan las capacidades de generación de los LLMs con técnicas de recuperación de información. De esta manera, los modelos pueden acceder a bases de datos externas, lo que les permite generar respuestas más precisas y contextuales.

En este trabajo se emplea la **Constitución Española** como caso de estudio para el desarrollo de un agente RAG. La Constitución es fragmentada en secciones más manejables mediante estrategias de chunkerización, evaluadas y comparadas para determinar su eficacia. Finalmente, se implementa un agente capaz de responder preguntas relacionadas con la Constitución utilizando estas técnicas avanzadas de recuperación.

## Estructura del Proyecto

- **Comparación de métodos de chunkerización:** Se analizan y comparan diversas técnicas de chunkerización para la segmentación óptima de los textos legales.
- **Desarrollo de un agente LLM:** Se diseña un agente capaz de responder preguntas relacionadas con la **Constitución Española**, proporcionando respuestas precisas y contextualizadas.
- **Marco teórico del estado del arte:** Se revisa la literatura existente sobre los **sistemas RAG** y las metodologías más recientes en el uso de LLMs.

## Tecnologías Utilizadas

- **Modelos de Lenguaje:** GPT-3.5-Turbo y GPT-4 para generación y evaluación de respuestas.
- **Chunkerización:** Se implementan y evalúan varias estrategias para mejorar la gestión de grandes volúmenes de información.
- **Retrievers:** Uso de técnicas de recuperación avanzadas para aumentar la relevancia y precisión de las respuestas.
- **Embedding Models:** Para transformar fragmentos del documento en vectores que permitan la recuperación semántica de la información.
- **Evaluación de las metodologías de chunkerización usadas:** Se ha usado la librería llamaindex para eso.

## Diagrama de Arquitectura

![Diagrama arquitectura]("memoria/figuras/capitulo6/arquitectura.png")


## Resultados Esperados

Se espera que el sistema RAG desarrollado sea capaz de:

1. **Mejorar la precisión** en las respuestas proporcionadas por los modelos LLM al integrarse con información específica y actualizada.
2. **Evaluar la eficacia de las técnicas de chunkerización** para la segmentación de textos legales complejos como la **Constitución Española**.
3. **Desarrollar un agente capaz de responder preguntas** complejas, proporcionando un contexto adecuado y respuestas coherentes.

## Contribuciones
Este proyecto fue desarrollado por Álvaro Beltrán Camacho como parte de su Trabajo Fin de Máster (TFM) para el Máster Universitario en Inteligencia Artificial en el curso académico 2023-2024, bajo la dirección de Andrés Díaz-Pinto.
