# Genome Sequencing Analysis Project

This repository contains code and data for exploratory analysis of genome sequencing data, focusing on variant genotypes, population structure, and variant annotation. The main analysis is performed in a Jupyter notebook (`main.ipynb`).

## Project Structure

```
├── main.ipynb                # Main analysis notebook
├── datasets/                 # Input and processed data files
│   ├── *.vcf                 # Variant Call Format files
│   ├── *.csv                 # Genotype matrices and processed data
│   ├── *.xlsx                # Additional variant annotation
│   └── imp/                  # Important processed/filtered data
├── images/                   # Generated plots and visualizations
│   └── *.png                 # Figures from the analysis
└── .gitignore                # Git ignore rules
```

## Main Features
- **Genotype matrix processing** from VCF files
- **Exploratory data analysis**: genotype distribution, missingness, variant type counts
- **Dimensionality reduction**: PCA to visualize population structure
- **Clustering**: KMeans to identify genetic subgroups
- **Variant annotation and summary statistics**
- **Visualization**: Histograms, heatmaps, scatter plots, violin plots

## How to Use
1. **Open `main.ipynb` in Jupyter Notebook or VS Code.**
2. **Run the cells sequentially** to reproduce the analysis and visualizations.
3. **Input data** is expected in the `datasets/` folder. Processed and important files are in `datasets/imp/`.
4. **Generated figures** are saved in the `images/` directory.

## Inferences & Conclusions
- The analysis reveals genetic diversity, population structure, and key variants in the dataset.
- Visualizations help identify clusters, outliers, and variant types.
- The workflow supports quality control and biological interpretation of sequencing data.

## Requirements
- Python 3.8+
- Jupyter Notebook or VS Code
- Common Python libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `plotly`

Install dependencies with:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn plotly
```

## License
This project is for educational and research purposes. Please cite appropriately if used in publications.

---

**For questions or contributions, please open an issue or pull request.**
