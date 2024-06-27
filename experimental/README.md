This folder contains our effort to reformat and clean [the experimental dataset of battery materials](https://doi.org/10.1038/s41597-020-00602-2), which was auto-generated using ChemDataExtractor. `battery_ultra_cleaned.csv` is the the recommanded cleaned version to use. Please refer to `workflow.ipynb` for further details.  


Files:
---
- `battery.csv`: the original published dataset 
- `workflow.ipynb`: the notebook that processes and cleans the original dataset 
---
- `battery_clean.csv`: the cleaned dataset
- `battery#2_partially_corrected.csv`: the file that contains manual corrections (Step 3 of the code section)
---
- `battery_further_cleaned.csv`: the cleaned dataset after applying the max coefficient cutoff (see 3.4 Coefficient-based data pruning and Step 3 of the code section)
---
- `battery_ultra_cleaned.csv`: the cleaned dataset after applying the max coefficient cutoff and the acronym / misrepresentation pruning (see 3.5 Dealing with acronyms and Step 3 of the code section)
- `misrepresented.csv`: the file that identifies instances with misrepresented formulas 
---
- `periodic_table.csv`: a periodic table containing elements and their properties. Could be used for feature encoding. 
