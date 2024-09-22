# Data-Science-Project-in-Remote-Sensing

### How to run the project:
All three .ipynb files should be placed in the same directory as the "reference" and "Sentinel - 1 CSAR" folders provided at the start of the project.
For example, in my case, the project folder is named e12229974, and it contains the following:
1. reference/
2. Sentinel - 1 CSAR/
3. 01_time_series_extraction.ipynb
4. 02_preprocessing.ipynb
5. 03_classification.ipynb


### Short description:
1. 01_time_series_extraction.ipynb (Run first):
This notebook extracts radar signal values from 31 .tif image files. Detailed explanations are provided in the comments within the code. After running this notebook, a CSV dataset named time_series_dataset.csv will be generated.

2. Once time_series_dataset.csv is created, it needs to be preprocessed. This notebook allows you to inspect and clean the dataset, preparing it for further analysis. The resulting dataset will be saved as working_dataset.csv.

3. 03_classification.ipynb (Run last):
In this notebook, two classifiers are tested: Random Forest and Time Series Transformer (TST). As before, all key details are available in the code comments.
