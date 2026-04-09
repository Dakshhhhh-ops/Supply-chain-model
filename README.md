# ML Supply Chain Logistics Model

A machine learning project for analyzing and predicting supply chain logistics patterns, enhanced with news sentiment and category data.

## Project Overview

This project combines supply chain logistics data with news information to build predictive models. The dataset includes supply chain metrics and categorized news data to capture external factors that may influence logistics operations.

## Files

### Datasets
- `dynamic_supply_chain_logistics_dataset.csv` - Main supply chain logistics dataset
- `merged_supply_chain_with_news.csv` - Combined logistics and news data
- `News_Category_Dataset_v3.json` - News articles categorized by topic

### Notebooks
- `main.ipynb` - Initial analysis and model development
- `main_corrected.ipynb` - Refined version with corrections and improvements
- `training.ipynb` - Model training and evaluation notebook

## Getting Started

1. **Install Dependencies**
   ```bash
   pip install pandas numpy scikit-learn jupyter
   ```

2. **Run the Notebooks**
   - Start with `main.ipynb` or `main_corrected.ipynb` for data exploration
   - Use `training.ipynb` for model training

3. **Data Processing**
   - Notebooks automatically load and preprocess the CSV and JSON datasets
   - Merged dataset is available in `merged_supply_chain_with_news.csv`

## Project Structure

```
ML-model/
├── README.md
├── .gitignore
├── dynamic_supply_chain_logistics_dataset.csv
├── merged_supply_chain_with_news.csv
├── News_Category_Dataset_v3.json
├── main.ipynb
├── main_corrected.ipynb
└── training.ipynb
```

## Notes

- Large dataset files are excluded from version control (see `.gitignore`)
- Use `main_corrected.ipynb` for the most up-to-date analysis
- Check `training.ipynb` for the final model implementation

## License

[Add your license here]

## Author

[Add author information here]
