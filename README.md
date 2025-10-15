# Movie Performance Prediction — Ratings & Casting

**Project:** Movie-Performance-Prediction-Based-on-Ratings-and-Casting  
**Author:** fredo123aaa (GitHub)  
**License:** MIT

---

## Project summary

This repository explores the relationship between a film’s economic performance (box office) and its **ratings** and **casting**. The analysis is presented as a sequence of Jupyter notebooks that cover data extraction, cleaning, feature engineering, exploratory analysis, and model experiments.

---

## Notebooks & key files

The repository contains multiple notebooks and datasets (notebook names listed as in the repo):

- `DataIMDb.ipynb` — likely responsible for downloading or collecting data from IMDb and other sources; initial data inspection and saving raw outputs.  
- `Extractfilminformation.ipynb` — scripts to extract structured film information (title, year, cast, crew, genres, ratings, links).  
- `ProcessingData.ipynb` — cleaning and processing steps: handling missing values, normalizing numeric fields, feature creation for modeling.  
- `filmInformation.ipynb` — additional processing / aggregation of film metadata, possibly joining cast and ratings to the main dataset.  
- `fredotests.ipynb` — experimental notebooks for modeling and sanity checks.  
- `final_cleaned_movies_data_f.csv`, `finaldata.csv`, and other CSVs — processed datasets ready for analysis or modeling.  
- `Final_Presentation.pdf` — the project presentation with results, charts, and conclusions.

---

## Goals & highlights

- Discover how cast composition and public ratings (IMDb, etc.) relate to box-office performance.  
- Build a reproducible pipeline: data acquisition → cleaning → feature engineering → modeling → evaluation.  
- Provide analyzed datasets and presentation-ready visuals summarizing key relationships.

---

## Requirements

Typical Python data-science stack (examples):
```bash
python >= 3.8
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
# Optional (if used in notebooks): requests, beautifulsoup4, imdbpy, tqdm, networkx
```

---

## Reproduce / Usage

1. Clone the repository:
```bash
git clone https://github.com/fredo123aaa/Movie-Performance-Prediction-Based-on-Ratings-and-Casting.git
cd Movie-Performance-Prediction-Based-on-Ratings-and-Casting
```

2. Open the notebooks with Jupyter Lab / Notebook:
```bash
jupyter lab
# or
jupyter notebook
```

3. Run the notebooks in order (suggested):
- `DataIMDb.ipynb` → `Extractfilminformation.ipynb` → `ProcessingData.ipynb` → `filmInformation.ipynb` → modeling/experiments notebooks (`fredotests.ipynb`, etc.)

4. Inspect processed datasets such as `finaldata.csv` before running heavy models.

---

## Results & deliverables

- Cleaned datasets (`final_cleaned_movies_data_f.csv`, `finaldata.csv`) for analysis and ML experiments.  
- Notebook-based pipeline showing data extraction, processing, and modeling steps.  
- `Final_Presentation.pdf` summarizing findings and visualizations.

---

## Contact / Credits

Project owner: `fredo123aaa` (GitHub). See repository for original notebooks and the MIT license. citeturn0view0
