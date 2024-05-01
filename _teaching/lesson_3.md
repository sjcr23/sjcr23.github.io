---
layout: page
img: assets/img/teaching/math.jpg
title: NumPy y vectores
description: Introducción a la Orientación a Objetos y a la biblioteca Pandas
cv_pdf: 3_NumPy, Vectores y Matrices.pdf
importance: 2
category: Python for Data Science (Spanish)
toc:
  sidebar: right
# related_publications: einstein1956investigations, einstein1950meaning
---

# Material de clase

\
Los materiales de la lección se encuentran disponibles en el ícono de color de la derecha.

---

# Créditos

\
**Autor :** [@KeithGalli](https://github.com/KeithGalli)  
Material recuperado de: [NumPy Tutorial.ipynb](https://github.com/KeithGalli/NumPy/blob/master/NumPy%20Tutorial.ipynb)

**Vídeo tutorial :** [Python NumPy Tutorial for Beginners](https://youtu.be/GB9ByFAIAH4)  

**Adaptado y traducido por :** [@sjcr23](https://github.com/sjcr23).

---

# Cuaderno de Jupyter

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/NumPy_KeithGalli.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/poo.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
