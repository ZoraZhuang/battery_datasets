# battery data from the materials project

This dataset contains battery data from the materials projects (https://next-gen.materialsproject.org/), using both the new and the old (legacy) APIs of the materials project. Each datapoint represents a voltage pair / sub-battery while a complete battery consists of one or more such voltage pairs, hence different datapoints may have the same battery id. 

Python notebooks to access and process the data are provided. To retrieve the data, relevant libraries need to be installed and API keys need to be obtained from the materials project website.

Note that the old api will eventually be replaced and the notebook might not work as expected. 

## files in the folders

in mp-legacy: 

- `mp_legacy.ipynb`: the notebook to access and process battery data from the legacy API
- `battery_intercalation.csv`: the raw data retrieved
- `mp_legacy.csv`: the processed dataset

in mp-legacy: 

- `mp-legacy+next-gen.ipynb`: the notebook to access and process battery data from the new API before merging it with data from the old API
- `mp_legacy.csv`: the processed data retrieved from the legacy API
- `battery_insertion.csv`: the raw data retrieved
- `mp_total.csv`: the complete processed dataset, including data from both APIs