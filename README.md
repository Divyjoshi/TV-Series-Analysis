# Analyze Series with NLP

## Project Overview
This project applies Natural Language Processing (NLP) techniques to analyze TV series scripts and dialogues. By processing and analyzing the textual content of popular TV shows, the project aims to extract insights about character relationships, sentiment patterns, and thematic elements throughout series seasons.

## Features
- Script parsing and preprocessing for TV series transcripts
- Character dialogue extraction and attribution
- Sentiment analysis across episodes and seasons
- Topic modeling to identify key themes and their evolution
- Character relationship network analysis
- Visualization of language patterns and character development

## Technologies Used
- **Python**: Core programming language
- **NLTK**: Natural Language Toolkit for text processing
- **spaCy**: Advanced NLP library for entity recognition and dependency parsing
- **Gensim**: Topic modeling and text vectorization
- **Scikit-learn**: Machine learning algorithms for classification and clustering
- **Pandas**: Data manipulation and analysis
- **Matplotlib/Seaborn**: Data visualization
- **NetworkX**: Character relationship network construction and analysis

## Getting Started

### Prerequisites
- Python 3.7+
- Required packages can be installed using:
```bash
pip install -r requirements.txt
```

### Installation
1. Clone this repository:
```bash
git clone https://github.com/abdullahtarek/analyze_series_with_NLP.git
cd analyze_series_with_NLP
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

### Usage
1. Prepare your TV series scripts in the required format
2. Run the preprocessing script:
```bash
python preprocess_scripts.py --input path/to/scripts
```

3. Perform analysis using the various modules:
```bash
python analyze_characters.py
python analyze_sentiment.py
python generate_topic_models.py
```

4. Generate visualizations:
```bash
python visualize_results.py
```

## Project Structure
```
analyze_series_with_NLP/
├── data/                  # Raw and processed script data
├── models/                # Trained NLP models
├── notebooks/             # Jupyter notebooks for exploration
├── src/                   # Source code
│   ├── preprocessing/     # Script preprocessing modules
│   ├── analysis/          # Analysis modules
│   ├── visualization/     # Visualization scripts
│   └── utils/             # Helper functions
├── results/               # Analysis results and visualizations
└── requirements.txt       # Project dependencies
```
