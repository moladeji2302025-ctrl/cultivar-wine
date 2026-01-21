# Wine Cultivar Classification

This project analyzes the sklearn wine dataset to classify wines into three cultivars (classes) using three machine learning models: Logistic Regression (LR), Decision Tree (DT), and Support Vector Machine (SVM).

## About the Project

The wine dataset contains results of chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. This project demonstrates how machine learning can classify wines based on their chemical properties.

### What are Cultivars?

Cultivars (cultivated varieties) are wine grape varieties that have been produced in cultivation by selective breeding. Different cultivars have distinct chemical compositions that influence:
- **Flavors**: From fruity to earthy notes
- **Aromas**: Floral, spicy, or woody scents
- **Overall wine profiles**: Body, tannin levels, acidity, and color

Wine cultivars are often associated with specific wine-producing regions, and chemical analysis can help identify their cultivar origin, which is crucial for quality control and authenticity verification.

## Features

The notebook includes:
1. **Data Loading**: Uses sklearn's wine dataset
2. **Data Exploration**: Displays dataset statistics and class distribution
3. **Model Development**: Implements three classification models (LR, DT, SVM)
4. **Performance Analysis**: Compares models using classification reports with metrics like:
   - Precision
   - Recall
   - F1-score
   - Accuracy

## Usage

### Google Colab (Recommended)

1. Open Google Colab: https://colab.research.google.com/
2. Upload the `wine_cultivar_classification.ipynb` notebook
3. Run all cells sequentially

### Local Jupyter Notebook

1. Install required dependencies:
   ```bash
   pip install scikit-learn pandas numpy jupyter
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook wine_cultivar_classification.ipynb
   ```

3. Run all cells in the notebook

## Requirements

- Python 3.x
- scikit-learn
- pandas
- numpy

## Dataset

The sklearn wine dataset contains:
- **Samples**: 178 wine samples
- **Features**: 13 chemical properties (alcohol, malic acid, ash, etc.)
- **Classes**: 3 wine cultivars

Reference: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html

## Results

All three models show strong performance in classifying wine cultivars:
- **Logistic Regression**: ~97% accuracy
- **Support Vector Machine**: ~97% accuracy
- **Decision Tree**: ~94% accuracy

The results demonstrate that machine learning can effectively distinguish between different wine varieties based on their chemical composition, which is valuable for:
- Quality control in wine production
- Authentication and fraud detection
- Understanding the relationship between chemistry and wine characteristics
