# 💻 Words2Code: Dual Modeling of NLP and Code Generation

## Overview

**Words2Code (W2C)** is my Master's thesis project in Software Engineering at The Hashemite University.

The project proposes a Transformer-based dual model capable of generating executable source code from natural language descriptions in **Python** and **Java**. It explores how Natural Language Processing (NLP) and modern Transformer architectures can help bridge the gap between human language and software development by automating code generation.

---

## Research Motivation

Modern software development demands faster development cycles while maintaining software quality and maintainability.

Writing code manually remains a time-consuming process, especially for repetitive or well-defined programming tasks. Recent advances in Natural Language Processing (NLP) have opened new opportunities for automatically translating human language into executable source code.

This research investigates whether a Transformer-based model can effectively generate accurate code from textual descriptions while supporting multiple programming languages.

---

## Research Objectives

- Develop a dual-language text-to-code generation model.
- Generate executable **Python** and **Java** source code from natural language descriptions.
- Investigate the effectiveness of Transformer-based architectures for code generation.
- Evaluate the model using standard NLP evaluation metrics.
- Compare the proposed model against existing approaches.

---

## Research Contributions

This research contributes to the field of Natural Language Processing and automated code generation by:

- Proposing a dual-language text-to-code generation model capable of generating both **Python** and **Java** source code.
- Fine-tuning a **T5 Transformer** model for multilingual code generation tasks.
- Evaluating the proposed model against established Transformer-based approaches, including **Base T5**, **CodeGen**, and **Small CodeParrot**.
- Investigating the effectiveness of multilingual datasets, particularly **XLCoST**, for natural language to code generation.
- Demonstrating the feasibility of multilingual code generation for software engineering applications through empirical evaluation.

## Dataset

The primary dataset used in this research is **XLCoST (Cross-Lingual Code Search and Generation)**.

XLCoST is a multilingual dataset designed for code intelligence tasks and includes parallel code examples across multiple programming languages, making it well suited for multilingual text-to-code generation.

The dataset is publicly available for research purposes and is **not owned or created by the author**.

Additional benchmarking and evaluation were also performed using **MBPP (Mostly Basic Programming Problems)** where appropriate during experimentation.

---

## Model

### Proposed Model

- Transformer Architecture
- **T5 (Text-to-Text Transfer Transformer)**
- Fine-tuned for multilingual text-to-code generation
- Generates both **Python** and **Java** code

---

## Methodology

The research followed the workflow below:

1. Literature Review
2. Dataset Selection
3. Data Preprocessing
4. Tokenization
5. Model Fine-tuning
6. Evaluation
7. Comparative Analysis
8. Result Interpretation

---

## Comparative Evaluation

The proposed **Words2Code (W2C)** model was evaluated against several existing Transformer-based approaches, including:

- Base T5
- CodeGen
- Small CodeParrot
- Proposed W2C Model

The evaluation measured each model's ability to generate executable code across programming tasks with varying complexity.

---

## Results

### Programming Languages

- Python
- Java

### Evaluation Metric

- **BLEU Score**

### Performance

- **BLEU Score:** **30.093**
- Successfully generated correct solutions for **4 out of 4** programming difficulty levels.

The evaluation demonstrates the potential of Transformer-based multilingual code generation while identifying opportunities for further improvement.

---

## Technologies Used

- Python
- Java
- PyTorch
- Hugging Face Transformers
- T5
- Jupyter Notebook

---

## Repository Contents

This repository contains:

- Project overview
- Research methodology
- Model description
- Evaluation summary
- Sample outputs
- Supporting resources

> **Note:** The trained model (~1 GB) is not included due to GitHub file size limitations.

---

## Future Work

Future improvements include:

- Support additional programming languages
- Improve code correctness on complex programming tasks
- Train on larger multilingual datasets
- Integrate Retrieval-Augmented Generation (RAG)
- Deploy the model as an interactive web application

---

## Academic Information

**Project**

Words2Code: Dual Modeling of NLP and Code Generation

**Degree**

Master's Thesis

**Institution**

The Hashemite University

Faculty of Graduate Studies

Department of Software Engineering

---

## Citation

If you use ideas or information from this repository, please cite the associated Master's thesis.

---

## Author

Ali Qaqour
