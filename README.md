# 📚 Retrieval Augmented Generation (RAG) - Píldora Explicativa

Bienvenido/a al repositorio del proyecto **Retrieval Augmented Generation (RAG)**, una introducción práctica y teórica a esta técnica innovadora que amplía las capacidades de los Modelos de Lenguaje de Gran Escala (LLM) con datos externos.

Este proyecto incluye:
- Un **notebook de Python** con el código implementado para entender y ejecutar un pipeline RAG.
- Un **documento PDF** explicativo que detalla los conceptos clave, ventajas y pasos técnicos de la implementación de RAG.

## 🎯 Objetivo del Proyecto
Este proyecto tiene como finalidad proporcionar una base sólida para que desarrolladores e investigadores puedan comprender e implementar sistemas RAG de manera modular y eficiente. Es ideal para quienes buscan potenciar aplicaciones de IA generativa con datos externos relevantes y actualizados.


## 📖 Contenidos

### 1. **Píldora Teórica (PDF)**
El archivo `RAG.pdf` explica:
- Qué es RAG y por qué es útil.
- Cómo RAG supera las limitaciones de los LLM tradicionales.
- Los pasos clave para implementar un pipeline RAG, incluyendo:
  - Ingesta y preprocesamiento de datos.
  - Vectorización e indexación.
  - Generación de respuestas contextualizadas.

### 2. **Código del Pipeline (Notebook)**
El archivo `Pipeline_RAG_Explanation.ipynb` incluye:
- Preparación de datos mediante loaders y splitters de LangChain.
- Generación de embeddings utilizando modelos como `text-embedding-ada-002`.
- Almacenamiento en bases vectoriales como FAISS.
- Generación de respuestas enriquecidas con contexto mediante LLM.


## 🚀 Instrucciones de Uso

### Requisitos
- Python 3.9 o superior
- Bibliotecas: `langchain`, `faiss`, `openai`, `pandas`, `PyPDF2` (ver `requirements.txt` para detalles)


### Instalación
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/pildora-rag.git
   cd pildora-rag

2. Instala las dependencias:
    ```bash
    pip install -r requirements.txt


### Ejecución

Abre el archivo Pipeline_RAG_Explanation.ipynb en Jupyter Notebook o tu editor de preferencia.

Sigue las celdas en orden para entender y ejecutar el pipeline.
