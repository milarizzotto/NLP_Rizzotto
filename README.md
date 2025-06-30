Bienvenidos :) 
En este repositorio se encuentra mi proyecto (TP1 + TP2) de *Procesamiento del Lenguaje Natural*:

# Asistente Conversacional Especializado en "Pradera" (Juego de Mesa)
Este repositorio contiene el desarrollo de un asistente experto en el juego de mesa Pradera, construido en dos etapas principales:

## 🧩 TP1 – Procesamiento y recuperación de información
- Web scraping multilingüe y limpieza de texto.
- Vectorización con embeddings y búsqueda semántica.
- Comparación de distancias (coseno, euclídea, etc.) y visualización en 3D.
- Extracción de POS y NER para búsqueda filtrada por sustantivos.
- Detección de idioma y análisis de sentimiento en reseñas.
- Clasificación supervisada de +300 preguntas según su fuente ideal de respuesta.

## 🤖 TP2 – Agente autónomo ReAct en LangChain
- Agente de tipo ReAct conectado a cinco herramientas:
  - Recuperación de documentos (RAG + rerank).
  - Consultas tabulares.
  - Consultas gráficas (Neo4j).
  - Wikipedia.
  - DuckDuckGo.
- Implementado en Colab usando **Together.ai** con el modelo `Mistral-7B-Instruct`.
- Multilingüe, sigue formato `Thought → Action → Observation → Final Answer`.
- Detecta idioma de entrada y responde en el mismo idioma.

**Todo el código es ejecutable desde Google Colab y está organizado por etapas.**
