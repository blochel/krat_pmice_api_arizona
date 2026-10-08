# Kangaroo Rats and Pocket Mice in Arizona

This project uses the [iNaturalist API](https://www.inaturalist.org/) to
retrieve and analyze observations of kangaroo rats and pocket mice in Arizona.

## Notebook

[`krat_pmice_api.ipynb`](krat_pmice_api.ipynb) includes:

- iNaturalist API requests filtered to Arizona
- 2025 monthly observation totals for kangaroo rats and pocket mice
- A comparison chart of monthly observations
- Species-level summaries from the returned observation sample
- A visualization of the most frequently represented species

## Important note

These data represent observations submitted to iNaturalist, not direct
measurements of animal abundance. Counts can also reflect observation effort,
weather, animal activity, accessibility, and other reporting factors.

## Running the notebook

Install the required Python packages if needed:

```bash
pip install requests pandas matplotlib
```

Then open `krat_pmice_api.ipynb` in Jupyter Notebook, JupyterLab, or VS Code
and run the cells from top to bottom. The notebook retrieves current API
responses when its cells are executed.
