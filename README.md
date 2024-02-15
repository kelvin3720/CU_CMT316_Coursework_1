# CU_CMT316_Coursework_1
Coursework 1 for CMT316 Applications of Machine Learning: Natural Language Processing and
Computer Vision

This notebook can also be viewed in Google Colab from [this](https://colab.research.google.com/drive/1OOEmi2t9ct1QDsXbI5f9u3ldBIDCrktm?usp=sharing) link (No editing permission is granted).

## How to run
There are 2 ways to run this notebook, Google Colab (preferred) or run locally (Linux)

### Google Colab
1. Download and open the part_2.ipynb in Google Colab
2. Upload the bbc.zip to the `Files` session
3. Run `!unzip bbc.zip` in one of the cells
4. Run `!ls` to make sure the unzipped bbc folder is at the current working directory, move the folder and its content to the current working directory of the notebook if not.
5. Click Runtime -> Run all
6. The final result (the model with 3 features) will be shown at the bottom of the notebook

### Local (Linux)
1. Download and open the part_2.ipynb in Jupyter Notebook
2. Install the required modules by `pip install -r requirements.txt` in your enviornment
3. Install the English model for spacy by `python -m spacy download en`
4. Make sure the `bbc` folder is at the same path with the ipynb file
5. Run all cells
6. The final result (the model with 3 features) will be shown at the bottom of the notebook