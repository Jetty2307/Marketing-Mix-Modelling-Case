# MMM Case

This repo contains a basic Marketing Mix Modeling notebook. Based on publicly available data and PyMC package, contains marketing data for different channels.

## File

- `case_MMM.ipynb` — main notebook

## Data

The notebook expects `test_data.csv` in the project folder.

Required columns:
- `start_of_week`
- `revenue`
- `spend_channel_1` to `spend_channel_7`

## Run

```bash
pip install pandas numpy matplotlib seaborn pymc arviz pytensor pymc-marketing scikit-learn jupyter
jupyter notebook case_MMM.ipynb
```
