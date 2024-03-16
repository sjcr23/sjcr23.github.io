---
layout: page
img: assets/img/projects/python.jpg
title: Lección N°1 Fundamentos de Python
description: Introducción a conceptos básicos de Python. 
cv_pdf: 1_Fundamentos de Python.pdf
importance: 1
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
**Autor :** [@kenjyco](https://gist.github.com/kenjyco)  
Material recuperado de : [kenjyco/01-Learning-Python3.md](https://gist.github.com/kenjyco/69eeb503125035f21a9d)

**Adaptado y traducido por :** [@mbiarreta](https://github.com/MBiarreta) y [@sjcr23](https://github.com/sjcr23).

---

# Cuaderno de Jupyter

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/Fundamentos_de_Python.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}


