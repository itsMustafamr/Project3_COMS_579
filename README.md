# QTL Text Analysis Project 3 - COMS 579

This project builds upon the methodologies developed in Project 2 by exploring advanced techniques for generating and evaluating trait-based titles from QTL-related texts. The focus is on comparing various approaches to title generation, including:

- **BART-based Title Generation** (`cl_bart_based_csvsave_3.ipynb`)
- **Rule-based Title Generation** (`rule_based_titles.csv`)
- **Hybrid Title Generation** (`hybrid_titles.csv`)

Each method aims to enhance the extraction and representation of QTL-relevant traits through different natural language processing techniques.

## 🔧 Setup

Ensure you have Python 3.8+ installed, along with Jupyter Notebook and the necessary libraries. Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/itsMustafamr/Project3_COMS_579.git
cd Project3_COMS_579
```

## 🚀 Execution Instructions

### BART-based Title Generation

Launch the Jupyter Notebook to execute the BART-based title generation process:

```bash
jupyter notebook cl_bart_based_csvsave_3.ipynb
```

This notebook utilizes a pre-trained BART model to generate titles based on QTL-related text inputs.

### Rule-based Title Generation

Review the `rule_based_titles.csv` file to examine titles generated through manual rule-based methods. This approach relies on predefined patterns and keyword matching to extract relevant traits.

### Hybrid Title Generation

The `hybrid_titles.csv` file contains titles produced by combining both BART-generated and rule-based methods, aiming to leverage the strengths of each approach for improved accuracy.

## 📊 Results

A comprehensive analysis comparing the effectiveness of each title generation method is documented in the `579_Project_3.pdf` file. This report includes evaluations based on accuracy, relevance, and consistency with QTL traits.
