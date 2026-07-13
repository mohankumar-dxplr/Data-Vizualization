# Data Visualization with Matplotlib & Seaborn

An educational project exploring Python data visualization through **Matplotlib** and **Seaborn**, using **IPL cricket statistics** and classic datasets as real-world examples.

## Contents

### Matplotlib —  `Matplotlib/matplotlib.ipynb`

Covers the foundational plotting library with cricket data:

- 2D line plots, scatter plots
- Bar charts (simple, horizontal, grouped)
- Custom styling: colors (hex), linestyles, linewidths, markers, marker sizes
- Labels, titles, legends, axis limits, grids
- Loading and plotting from CSV with pandas

### Seaborn — `Data vizualization with Seaborn.ipynb`

Covers statistical data visualization with the `tips` and `iris` built-in datasets:

- **Categorical scatter:** `stripplot`, `swarmplot`
- **Categorical distribution:** `boxplot`, `violinplot`
- **Categorical estimate:** `barplot`, `pointplot`, `countplot`
- **Regression:** `regplot`, `lmplot`, `residplot`
- **Faceting:** `FacetGrid`, `catplot` with `col` / `row` parameters
- Parameters: `hue`, `split`, `color`, `estimator`

## Repository Structure

```
Data-Vizualization/
├── Data vizualization with Seaborn.ipynb   # Seaborn tutorial
├── Data Vizualization with Seaborn.pdf     # Exported PDF with outputs
├── Matplotlib/
│   ├── matplotlib.ipynb                    # Matplotlib tutorial
│   ├── matplotlib.pdf                      # Exported PDF with outputs
│   ├── batter.csv                          # IPL batsman career stats
│   ├── batsman_season_record.csv           # Season-wise runs for 5 batsmen
│   ├── vk.csv                              # Virat Kohli per-match runs
│   ├── sharma-kohli.csv                    # Rohit vs Kohli yearly comparison
│   ├── gayle-175.csv                       # Chris Gayle 175* ball-by-ball
│   ├── iris.csv                            # Fisher's Iris dataset
│   ├── IPL_Ball_by_Ball_2008_2022.csv      # 226K-row IPL ball-by-ball data
│   └── big-array.npy                       # NumPy array (demo purposes)
├── requirements.txt
└── README.md
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/Data-Vizualization.git
   cd Data-Vizualization
   ```

2. **Create and activate a virtual environment (recommended):**
   ```bash
   python -m venv venv
   .\venv\Scripts\activate    # Windows
   # source venv/bin/activate  # macOS/Linux
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```

   Then open either notebook.

## Datasets

| File | Description | Rows |
|------|-------------|------|
| `batter.csv` | IPL batsman career aggregates (runs, avg, SR) | 606 |
| `batsman_season_record.csv` | Yearly runs for 5 top IPL batsmen (2015–17) | 6 |
| `vk.csv` | Virat Kohli — runs per match | 142 |
| `sharma-kohli.csv` | Rohit Sharma vs Virat Kohli (2008–2017) | 11 |
| `gayle-175.csv` | Ball-by-ball scores from Gayle's 175* innings | 7 |
| `iris.csv` | Standard Iris flowers dataset | 151 |
| `IPL_Ball_by_Ball_2008_2022.csv` | Every ball of every IPL match (2008–2022) | ~226K |

## Dependencies

- `numpy`, `pandas` — data manipulation
- `matplotlib` — core plotting library
- `seaborn` — statistical data visualization
- `jupyter` / `ipykernel` — notebook environment
