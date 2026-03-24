# Data Quality and Query Correction System using Multi-Method Approaches

A data-driven system that detects and corrects query inconsistencies using multiple approaches including rule-based methods, embedding models, and LLM-based techniques.

---

##  Overview

Real-world datasets often contain inconsistencies such as:

* Synonym mismatches
* Logical errors
* Ambiguous queries

This project builds a system to:

* Generate synthetic datasets with controlled errors
* Apply multiple correction techniques
* Compare performance across methods

---

##  Key Features

* Synthetic data generation pipeline
* Multiple correction approaches:

  * Rule-based
  * Advanced rule-based
  * Embedding-based
  * LLM-based
* Comparative analysis of methods
* Image + CSV dataset handling

---

##  Project Structure

```plaintext
data/        → datasets and images  
src/         → data generation pipeline  
methods/     → 4 different correction approaches  
results/     → outputs and evaluation  
docs/        → project report  
```

---

##  Methodology

### 1. Data Generation

* Created datasets with controlled variations:

  * Perfect data
  * Synonym-based errors
  * Logical inconsistencies

### 2. Query Correction Methods

#### Rule-Based

* Uses predefined rules for correction

#### Advanced Rule-Based

* Handles complex variations and patterns

#### Embedding-Based

* Uses semantic similarity for correction

#### LLM-Based

* Uses language models for intelligent query correction

---

##  Datasets

* Dataset A → Perfect data
* Dataset B → Synonym variations
* Dataset C → Logical errors

---

##  Observations

* Rule-based methods are fast but limited
* Embedding-based methods improve semantic understanding
* LLM-based approaches provide highest flexibility
* Trade-off between accuracy and computational cost

---

##  Design Trade-offs

| Method        | Strength        | Limitation      |
| ------------- | --------------- | --------------- |
| Rule-Based    | Fast            | Rigid           |
| Advanced Rule | Better coverage | Complex rules   |
| Embedding     | Semantic        | Requires tuning |
| LLM           | Flexible        | Expensive       |

---

##  How to Run

1. Generate data:

```bash
python src/data_generation/data_generator_local.py
```

2. Run methods:

* Open notebooks in `methods/`
* Execute cells step-by-step

---

## 🛠️ Tech Stack

* Python
* Pandas / NumPy
* NLP techniques
* Jupyter Notebooks

---

##  Applications

* Data cleaning pipelines
* Query correction systems
* NLP preprocessing
* Intelligent search systems

---

##  Contributors

* Shreyas K S
