# 📚 Píldora RAG (Retrieval Augmented Generation)

Bienvenido/a al repositorio del proyecto **Píldora RAG (Retrieval Augmented Generation)**, una introducción práctica y teórica a esta técnica innovadora que amplía las capacidades de los Modelos de Lenguaje de Gran Escala (LLM) con datos externos.

Este proyecto incluye:
- Un **notebook de Python** con el código implementado para entender y ejecutar un pipeline RAG.
- Un **documento PDF** explicativo que detalla los conceptos clave, ventajas y pasos técnicos de la implementación de RAG.


  
[Mira aquí la presentación](https://mariarosacuenca.my.canva.site/rag)

## 🎯 Objetivo del Proyecto
Este proyecto tiene como finalidad proporcionar una base sólida para que desarrolladores e investigadores puedan comprender e implementar sistemas RAG de manera modular y eficiente. Es ideal para quienes buscan potenciar aplicaciones de IA generativa con datos externos relevantes y actualizados.


## 📖 **Contenido**

El documento PDF proporciona una guía teórica y práctica para entender e implementar RAG. Las secciones incluidas son:

1. **Introducción**
   - ¿Por qué RAG?
   - ¿Qué es RAG?

2. **Fases del RAG**
   - **Recuperación**: Localización de información relevante en bases de datos o documentos.
   - **Aumento**: Enriquecimiento del contexto de las consultas con información recuperada.
   - **Generación**: Creación de respuestas precisas y contextualizadas utilizando LLM.

3. **Implementación de un Sistema RAG**
   - **Preparación e Ingesta de Datos**:
     - Document Loaders
     - División en Fragmentos (Chunks)
   - **Vectorización e Indexación**:
     - Generación de Embeddings.
     - Bases de Datos Vectoriales.

4. **Generación de Respuestas**
   - Uso de LLM para integrar el contexto y generar respuestas.
   - Plantillas de prompts para guiar al modelo.
   - Citación de fuentes para transparencia.

5. **Evaluación y Optimización**
   - **Métricas para evaluar LLMs**:
     - Métricas basadas en LLMs.
     - Métricas tradicionales de NLP:
   - **Evaluación en RAG**:
     - Recuperación: Context Recall (recuperación del contexto relevante).
     - Generación: Fidelidad, relevancia, corrección y similitud semántica.

6. **Ejemplo Práctico**
   - Aquí se hace referencia al archivo Pipeline_RAG_Explanation.ipynb.

7. **Referencias**
   - Fuentes bibliográficas y recursos adicionales para profundizar:


Este PDF es una referencia integral para aprender sobre RAG y su implementación. ¡Explóralo para obtener todos los detalles!


## 🚀 Instrucciones de Uso

### Requisitos
- Python 3.9 o superior
- Bibliotecas: `langchain`, `faiss`, `openai`, `pandas`, `PyPDF2` (ver `requirements.txt` para detalles)


### Instalación
1. Clona este repositorio:
   ```bash
   git clone https://github.com/mcuencac/pildora-rag.git
   cd pildora-rag

2. Instala las dependencias:
    ```bash
    pip install -r requirements.txt


### Ejecución

Abre el archivo Pipeline_RAG_Explanation.ipynb en Jupyter Notebook o tu editor de preferencia.

Sigue las celdas en orden para entender y ejecutar el pipeline.
