# Texter:  A text summarisation tool.
This is an NLP based text summarisation tool. It utilizes an unsupervised learning approach using an extractive summarisation technique.

Today, our world is parachuted by the gathering and dissemination of huge amounts of data. In fact, the International Data Corporation (IDC) projects that the total amount of digital data circulating annually around the world would sprout from 4.4 zettabytes in 2013 to hit 180 zettabytes in 2025. That’s a lot of data!

With such a big amount of data circulating in the digital space, there is need to develop machine learning algorithms that can automatically shorten longer texts and deliver accurate summaries that can fluently pass the intended messages.

Furthermore, applying text summarization reduces reading time, accelerates the process of researching for information, and increases the amount of information that can fit in an area.



## Tech Stack

![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white) 
![Nltk](https://img.shields.io/badge/Nltk-red?style=for-the-badge&color=red)
![NumPy](https://img.shields.io/badge/Numpy-blue?style=for-the-badge)
![NetworkX](https://img.shields.io/badge/NetworkX-green?style=for-the-badge)


Apart from all these dependencies, various algorithms are applied to successfully generate the summary of any huge paragraph.

* Cosine Similarity - Cosine distance is a measure of similarity between two vectors in a multidimensional space. It calculates the cosine of the angle between the vectors, which indicates how similar or dissimilar they are.

* TextRank - TextRank is a graph-based ranking algorithm used for text summarization and keyword extraction. It is inspired by Google's PageRank algorithm, which ranks web pages based on their importance in the web graph. TextRank applies a similar concept to sentences or words in a text document.

For implementing this tool, first we need to download a text corpus from the Natural Language Toolkit library (Nltk). And after all the processing, the vector data is stored in a graph-like structure. This is where the NetworkX library comes into play. 

NetworkX is a package for the Python programming language that's used to create, manipulate, and study the structure, dynamics, and functions of complex graph networks.
