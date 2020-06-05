## COVID-19 Exploratory Analysis of the Research Papers

With the current novel coronavirus COVID-19 pandemic, a lot of research is going on to deal with this crisis. To aid the global research community, an open dataset of scholarly articles called the COVID-19 Open Research Dataset (CORD-19) has been prepared. The CORD-19 dataset contains around 57,000 scholarly articles, including over 45,000 with full text about COVID-19, SARS-CoV-2, and related coronaviruses. The goal is to derive new insights that can help in countering this infectious disease. Going over so many articles manually is tedious, hence in this project we have conducted an exploratory analysis of this dataset to get a better understanding of it.

CORD-19-research-challenge file should be downloaded from Kaggle before running the notebooks. This is done because the data is too large and could not be uploaded directly due to file size restrictions.

The order of running notebooks is as follows:

1. download-kaggle-dataset: this will use the Kaggle API and download the dataset in the appropriate folder, check this documentation to install and use Kaggle API.
2. commercial-data and non-commercial-data: these notebooks can run in parallel to generate 2 separate csv files one each for commercial and non-commerical.
3. consolidate-data: this notebook combines the commercial and non-commercial csv’s into a single dataset
4. generate-tables: this notebook will create the LIB, TOKEN, VOCAB files
5. analysis: this notebook will create TFIDF, perform PCA, generate word embeddings and perform sentiment analysis
6. LDA: this notebook performs topic modeling on the dataset.

Detailed analysis and interpretations from them are provided in the `report.pdf` file.
