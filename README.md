# Introduction to Machine Learning with Python

Notebooks and code while reading "Introduction to Machine Learning with Python" by Andreas C. Müller & Sarah Guido.

## 📚 About

This repository contains my learning journey through the book "Introduction to Machine Learning with Python: A Guide for Data Scientists" (O'Reilly Media). It includes Jupyter notebooks, code examples, exercises, and notes organized by chapter.

## 📖 Book Information

- **Title**: Introduction to Machine Learning with Python
- **Authors**: Andreas C. Müller & Sarah Guido
- **Publisher**: O'Reilly Media
- **ISBN**: 978-1-449-36941-5

## 🎯 Learning Objectives

- Understanding fundamental machine learning concepts
- Practical implementation using scikit-learn
- Data preprocessing and feature engineering
- Model evaluation and selection
- Working with different types of machine learning algorithms
- Best practices for machine learning workflows

## 📁 Project Structure

```
introduction_to_ml_with_python/
├── README.md
├── notebooks/
│   ├── chapter_01/          # Introduction
│   ├── chapter_02/          # Supervised Learning
│   ├── chapter_03/          # Unsupervised Learning
│   ├── chapter_04/          # Representing Data and Engineering Features
│   ├── chapter_05/          # Model Evaluation and Improvement
│   └── chapter_06/          # Algorithm Chains and Pipelines
├── data/                    # Datasets used in examples
├── exercises/               # Practice exercises and solutions
└── notes/                   # Learning notes and summaries
```

## 🛠️ Setup

### Prerequisites

- Python 3.8 or higher
- pip or conda package manager

### Installation

1. Clone this repository:
```bash
git clone https://github.com/hugoangeles0810/introduction_to_ml_with_python.git
cd introduction_to_ml_with_python
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

### Required Packages

- numpy
- pandas
- matplotlib
- scikit-learn
- jupyter
- scipy
- seaborn (optional, for enhanced visualizations)

## 📝 Usage

To run the notebooks:

```bash
jupyter notebook
```

Or using JupyterLab:

```bash
jupyter lab
```

Navigate to the `notebooks/` directory and open the chapter you're interested in.

## 📊 Topics Covered

- **Supervised Learning**
  - Classification (k-NN, Naive Bayes, Decision Trees, Random Forests, etc.)
  - Regression (Linear Regression, Ridge, Lasso, etc.)
  - Support Vector Machines
  - Neural Networks

- **Unsupervised Learning**
  - Clustering (k-Means, Agglomerative Clustering, DBSCAN)
  - Dimensionality Reduction (PCA, NMF, t-SNE)

- **Data Preprocessing**
  - Scaling and normalization
  - Categorical variables encoding
  - Feature engineering
  - Handling missing values

- **Model Evaluation**
  - Cross-validation
  - Grid search
  - Evaluation metrics
  - Bias-variance tradeoff

- **Pipelines**
  - Building machine learning pipelines
  - Feature unions
  - Model persistence

## 🔗 Resources

- [Official Book Website](https://www.oreilly.com/library/view/introduction-to-machine/9781449369880/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Book's GitHub Repository](https://github.com/amueller/introduction_to_ml_with_python)

## 📚 Notes

- This repository is for educational purposes
- Code examples are based on the book's content
- Some modifications and experiments may be included for deeper understanding
- Datasets are from the book's official repository or publicly available sources

## 🤝 Contributing

This is a personal learning repository, but suggestions and improvements are welcome!

## 📄 License

This repository is for educational purposes. Please refer to the original book for licensing information regarding the book's content.

## 🙏 Acknowledgments

- Andreas C. Müller & Sarah Guido for writing an excellent book
- O'Reilly Media for publishing
- The scikit-learn development team
