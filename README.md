# SharkTemp Insight

> **Problem:** Shark–human encounters are rising, but activity labels (e.g., swimming, surfing) don’t explain the spikes.  
> **Solution:** Merge 6,141+ GSAF shark attack cases with NOAA sea-surface temperature data to uncover temperature-driven risk patterns.

<!-- ![demo](docs/demo.gif) -->
---

## Quick Start

```bash
git clone https://github.com/SusanRobbins/shark-temp-insight.git
cd shark-temp-insight
pip install -r requirements.txt
jupyter notebook notebooks/analysis.ipynb
```
## Contents

- `notebooks/analysis.ipynb` — Full exploratory data analysis and cleaning workflow  
- `data/` — Raw and processed datasets (GSAF, NOAA sea-surface temperatures)  
- `src/` — Helper scripts for loading and merging data  
- `docs/` — Demo images and GIFs for blog or README use  

---

## Requirements

- Python 3.8+  
- See `requirements.txt` for dependencies (pandas, geopandas, seaborn, matplotlib, etc.)

---

## Author

**Susan Robbins**  
Technical writer & data enthusiast fascinated by sharks and sea science.  
[GitHub](https://github.com/SusanRobbins) · [Blog](https://medium.com/@susanrobbins_dev)
