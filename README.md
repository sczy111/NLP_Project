# NLP Project

## Overview
This repository contains the implementation for the NLP project tasks. All tasks are implemented within [`Project.ipynb`](Project.ipynb), which includes code cells annotated with task-specific comments. It contains the initial results.

## Prerequisites
- The project was developed with Python 3.12, other version may work as well.
- It is recommended to work within a Python virtual environment to avoid dependency conflicts with other projects.

## Setup
1. Clone the repository and navigate into the project directory.
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Project
1. Launch Jupyter and open the main notebook:
2. Run the notebook cells sequentially to reproduce the analysis and results for each task.

## Section should be run to generate the table and figure data in the report

The tables and figures in the report are generated from specific sections (tasks) of the main notebook file.  
Please run the corresponding task sections to reproduce each result:

- **TABLE I** and **Figure 2** → from **Task 1** section  
- **TABLE II**, **III**, **IV** → from **Task 2** section  
- **TABLE V** → from **Task 3** section  
- **TABLE VI** and **VII** → from **Task 4** section  
- **TABLE VIII** and **IX** → from **Task 5** section  
- **TABLE X** → from **Task 6** section  
- **TABLE XI** → from **Task 7** section  
- **TABLE XII** → from **Task 8** section  
- **TABLE XIII** and **XIV** → from **Task 9** section  
- **Figures 3–7** → from **Task 10** section  
- **Figures 8–10** → from **Task 11** section

All these sections are contained within the main Jupyter Notebook file  [`Project.ipynb`](Project.ipynb).

## Additional Notes
- The [`translations_cache/`](translations_cache) directory is used to cache translations for non-English corpora, which speeds up repeated runs of the notebook.
- Downloaded corpora for NLTK will be stored in your local NLTK data directory. Ensure you have the required permissions or configure `NLTK_DATA` accordingly.

## Troubleshooting
- If you encounter missing NLTK resources, run the appropriate `nltk.download()` commands within the notebook or in a separate Python session.
- For GPU acceleration with PyTorch, ensure the appropriate CUDA-enabled version is installed on your system.
