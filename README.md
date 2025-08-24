# Reddit Climate Change Analysis

A Jupyter notebook-based analysis of climate change discussions on Reddit, focusing on topic modeling and sentiment analysis. This project uses the dataset from [Zenodo](https://zenodo.org/records/15719951) which contains pre-collected Reddit data from r/climate and r/climatechange subreddits.

## Requirements

### Python & Environment
- Python 3.8 or newer
- Jupyter Notebook

### Key Libraries
- **Data Handling**: pandas, numpy
- **Text Analysis**: 
  - nltk
  - spacy
  - scikit-learn
- **Visualization**: matplotlib, seaborn, plotly
- **Machine Learning**: tensorflow-hub, umap-learn

1. Clone the repo:
```bash
git clone 

2. Set up your environment:
```bash
# Create a virtual environment
python -m venv venv

# Windows
.\venv\Scripts\activate

# macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

3. Install language models:
```python
# In Python
import nltk
nltk.download(['punkt', 'stopwords', 'wordnet'])

# In terminal
python -m spacy download en_core_web_sm
```

4. Download the dataset:
- Get the data file from [Zenodo](https://zenodo.org/records/15719951)
- Extract `data_reddit_paper1.7z` into the `data` directory

## Running the Analysis

1. Open `reddit_Paper1_main.ipynb`

2. The notebook will:
   - Process the Reddit data
   - Run topic modeling
   - Create visualizations
   - Show analysis results

Typical runtime is about 5 minutes for a full analysis if you downloaded the data from zenodo.

## Dataset Citation

If you use this dataset in your research, please cite:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15719951.svg)](https://doi.org/10.5281/zenodo.15719951) 
