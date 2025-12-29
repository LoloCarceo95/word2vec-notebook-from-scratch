# Word2Vec from Scratch (PyTorch)

Implementación **desde cero** de Word2Vec (Skip-gram con Negative Sampling) en PyTorch, con un enfoque didáctico y paso a paso.

El objetivo de este proyecto es **entender realmente** cómo funcionan los embeddings de palabras, sin usar implementaciones “caja negra”.

---

##  Contenido del notebook

El notebook incluye:

- Limpieza y tokenización del corpus (WikiText-2)
- Construcción del vocabulario y filtrado de palabras raras
- Subsampling de palabras frecuentes
- Generación del corpus numérico
- Dataset Skip-gram
- Negative Sampling
- Definición del modelo Word2Vec en PyTorch
- Entrenamiento desde cero
- Evaluación de embeddings:
  - similitud coseno
  - analogías (`king - man + woman ≈ queen`)
- Visualización de embeddings en 2D y 3D (PCA)

---

##  Conceptos clave

- Skip-gram
- Negative Sampling
- Embeddings como parámetros entrenables
- Distribución de muestreo negativa `P(w) ∝ f(w)^(3/4)`
- Geometría semántica en espacios vectoriales

---

## 🛠️ Tecnologías usadas

- Python 3
- PyTorch
- NumPy
- scikit-learn
- Matplotlib / Plotly
- Jupyter Notebook

---

##  Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/LoloCarceo95/word2vec-notebook-from-scratch.git
