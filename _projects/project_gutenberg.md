---
layout: page
title: Books Downloader
description: Download the top 100 EBooks last 30 days from Project Gutenberg.
img: assets/img/projects/projectgutenburg.jpg
importance: 2
category: Automation
toc:
  sidebar: right
# giscus_comments: true
---

This small project automates the task of downloading the top 100 books of the month from Project Gutenberg. Which was necessary for an academic project of the Operating Systems course, more information about the course project here: [sjcr23/projects/SO/Huffman_Algorithm](https://github.com/sjcr23/SO/tree/main/Proyectos/Algoritmo%20de%20Huffman).

# About Project Guntenberg

---

<div style="text-align:justify">
Project Gutenberg is an online library of free e-books, founded in 1971 by Michael Hart. Project Gutenberg is a non-profit initiative that seeks to digitize and distribute free public domain literary works<a href="https://www.gutenberg.org/">¹</a>. The project works thanks to the collaboration of thousands of volunteers from all over the world. These volunteers are in charge of digitizing the books, reviewing and correcting them to ensure the quality of the content. Its main objective is to democratize access to culture and knowledge, making available to anyone, anywhere in the world, a wide selection of classic and contemporary works. Project Gutenberg books can be freely downloaded in a variety of formats, including EPUB, MOBI, PDF and TXT. In addition, the library offers audiobooks for those who prefer to listen rather than read<a href="https://www.gutenberg.org/">¹</a>.
<br><br>
</div>

# Requirements

---

A script to download a certain list of books from [Project Gutenberg](https://www.gutenberg.org/). Guide made for Windows 10, it also works in others OS if you get correctly the requirements and the webdriver. You will need to install the following:

- [Python & Pip](https://www.python.org/)
- [Selenium library](https://pypi.org/project/selenium/)

    ```bash
    pip install -U selenium
    ```

- [Google Chrome](https://www.google.com/chrome/)
- [Google Chrome web driver](https://chromedriver.chromium.org/downloads)

> Note: In this repository is already included the [ChromeDriver 114.0.5735.90](https://chromedriver.storage.googleapis.com/index.html?path=114.0.5735.90/). For the future, you may update the driver or your Google Chromes's version.



# Usage
---

1. Create a folder named `output` in the same directory level with `downloader.py`, or just make sure that the variable `resources_path` has the same name as the output folder created.

    ```python
    # Directory to file storage "output"
    resources_path = "output"
    ```

3. Run  `downloader.py` from the folder where it is located.

    ```bash
    python downloader.py
    ```

# Demo video
--- 

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/gutenberg_demo.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    A little example of how to run the demo.
</div>




