# Information Extraction From Scientific Publication

This repository contains work done as part of AI-3 course by [Univ.ai](https://www.univ.ai/).</br> 
Our team - Himanshu, Aayush, Srish

## Project

Extract key information from scientific papers using NER

<img src="https://github.com/HimanS-sys/WIESP-NER/blob/main/assets/images/ner_intro.png">

- The number of scientific papers published per year has exploded in recent years, strengthening its value as one of the main drivers for scientific progress.
- In astronomy alone, more than 41,000 new articles are published every year and the vast majority are available either via an open-access model or via pre-print services.
-  Indexing the article’s full-text in search engines helps discover and retrieve vital scientific information to continue building on the shoulders of giants, informing policy, and making evidence-based decisions.
- Nevertheless, it is difficult to navigate in this ocean of data; finding articles rely heavily on string matching searches and following citations/references.
- NER helps us extract key information from scientific papers which can help search engines to better select and filter articles.

## Data

- The dataset used in this project is from Workshop on Information Extraction from Scientific Publications (WIESP/2022).
- It comprises of text fragments from astrophysics papers, provided by the NASA Astrophysical Data System with manually tagged astronomical facilities and other entities of interest (e.g., celestial objects).
- [Click Here!](https://huggingface.co/datasets/adsabs/WIESP2022-NER) to access the data.

## Methodology and Result
- Following poster shows our methodology and results in breif.

<img src="https://github.com/HimanS-sys/WIESP-NER/blob/main/assets/images/ner_poster.jpg">

- [Notebook](https://github.com/HimanS-sys/WIESP-NER/blob/main/NER_main.ipynb) used for modelling.
- [Files](https://github.com/HimanS-sys/WIESP-NER/tree/main/Streamlit%20%2B%20Test%20Prediction%20File) used for streamlit demo.
- [Presentation slides](https://github.com/HimanS-sys/WIESP-NER/blob/main/Presentation/ner_slides.pdf) for more detailed explaination.
- [Video presentation](https://github.com/HimanS-sys/WIESP-NER/blob/main/Presentation/presentation.mp4) along with app demo.
