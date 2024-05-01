---
layout: page
img: assets/img/teaching/pandas.jpg
title: POO & Pandas
description: Introducción a la Orientación a Objetos y a la biblioteca Pandas
cv_pdf: 2_Introducción a POO y Pandas.pdf
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
**Autor :** [@Ikuffo](https://github.com/lkuffo)  
Material recuperado de: [pandas-notebook.ipynb](https://github.com/lkuffo/leonardo-youtube/blob/master/Machine%20Learning/Pandas/pandas-notebook.ipynb)

**Vídeo tutorial :** [Pandas en 30 minutos (Python)](https://www.youtube.com/watch?v=8ASjvOIyyl8)

**Adaptado y traducido por :** [@sjcr23](https://github.com/sjcr23).

---

# Cuaderno de Jupyter

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/poo.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/poo.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
