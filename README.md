<h2 align="center">Antoni Dłużewski</h2>

<p align="center">
  ML / AI engineering · MSc Data Science & AI at Université Paris-Saclay
  <br>
  <a href="mailto:dluzewskiantoni@gmail.com">dluzewskiantoni@gmail.com</a> · Paris
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square" alt="SQL">
</p>

---

I like ML projects where you can measure whether the thing actually works: a chess engine you can play against the old version, a retrieval system with a test set, a model with a number next to it that someone else can reproduce.

**Right now:** doing my master's in Paris and looking for an **AI / ML Engineer internship**.

**This summer** I was an AI research intern at **Ultima-I**. I studied why a mortality model trained on ICU data (MIMIC-III) misses specific groups of patients. Then I used an LLM to generate synthetic patient records targeted at those groups, and measured what that does to the model, both on those groups and overall. The short version: it can help a lot locally, and adding too much can quietly hurt everyone else. The article is under review.

### Projects

<table>
<tr>
<td width="50%" valign="top">

**[neural-chess-eval](https://github.com/antony0167/neural-chess-eval)**

A small NNUE-style network that evaluates chess positions. It's trained on 600k positions labelled by Stockfish, runs inside my own alpha-beta search with incremental updates, and is tested in engine-vs-engine matches with Elo and confidence intervals.

`PyTorch` `NumPy` `python-chess`

</td>
<td width="50%" valign="top">

**[paper-rag](https://github.com/antony0167/paper-rag)**

Question answering over arXiv papers with cited answers. It combines hybrid BM25 + embedding search, a cross-encoder reranker, and an evaluation harness that compares four retrievers and RAG against closed-book answers. Includes a hard cost cap for paid APIs.

`sentence-transformers` `FastAPI` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[PathFinding](https://github.com/antony0167/PathFinding)**

DFS, BFS, greedy best-first and A* on generated mazes, with pictures of what each one explores. A* finds the same shortest path as BFS while looking at half as many cells.

<img src="https://raw.githubusercontent.com/antony0167/PathFinding/master/images/comparison.png" alt="DFS, BFS, Greedy and A* compared on one maze" width="100%">

</td>
<td width="50%" valign="top">

**[Chess-in-c-](https://github.com/antony0167/Chess-in-c-)**

My first chess program, from my bachelor's: two-player chess in C++ with an SFML window. Move rules, check detection and en passant are all written from scratch.

`C++17` `SFML` `CMake`

</td>
</tr>
</table>

### Background

- **2025 – now:** MSc Data Science & AI, Université Paris-Saclay
- **Summer 2026:** AI research intern, Ultima-I
- **Summer 2025:** Frontend developer, VonRoll Infratec (Angular micro-frontends)
- **2021 – 2025:** BSc Applied Computer Science, University of Wrocław (with an Erasmus year at Université de Lille)
- Tutoring high-school maths since 2023

### Off the keyboard

Chess (hence two of the projects above), sailing, 15 years of violin, and a 14-second Rubik's cube personal best.

<sub>Languages: Polish (native), English (C1), French (B2), Spanish (A2)</sub>
