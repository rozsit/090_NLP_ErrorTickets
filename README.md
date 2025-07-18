# Ticket Clustering and Analysis Project

This project is an automated text analysis and clustering system designed to process and categorize Hungarian-language support tickets.
It leverages the [HuSpacy](https://github.com/huspacy/huspacy) NLP toolkit for Hungarian text preprocessing and is fully designed to run in a Jupyter Notebook environment.

## Key Features

* **Text Preprocessing**: Lemmatization and stop-word removal powered by HuSpacy.
* **Keyword-Based Clustering**: Automatic categorization of tickets using a predefined keyword dictionary.
* **Data Visualization**: Word clouds, temporal trends, and cluster distribution visualizations.

## Installation

Follow these steps to set up the environment and run the project in Jupyter Notebook:

1. Clone the repository:
   bash
   git clone https://github.com/username/project.git
   cd project
2. Install the required Python packages: Open a terminal or command prompt, and run:
   bash
   pip install -r requirements.txt

3.Install Jupyter Notebook (if not already installed):
bash
pip install notebook

4. Install the HuSpacy model:
   bash
   pip install huspacy

&nbsp;  import huspacy

&nbsp;  # Download the latest CPU optimized model

&nbsp;  huspacy.download()

4. Open the Jupyter Notebook:
   bash
   jupyter notebook
   Navigate to the project directory and open the NLP\_Demo\_Ticket\_Proc\_Hun-Dict.ipynb file.



6.Running the Notebook
Make sure your ticket data is saved as a CSV file (tickets\_generated\_2.csv) and placed in the project root directory.



## Acknowledgments

This project relies on the outstanding HuSpacy NLP toolkit. Special thanks to Zsolt Gyarmati for developing and maintaining HuSpacy.



## Citation

@InProceedings{HuSpaCy:2023,
    author= {"Orosz, Gy{\"o}rgy and Szab{\'o}, Gerg{\H{o}} and Berkecz, P{\'e}ter and Sz{\'a}nt{\'o}, Zsolt and Farkas, Rich{\'a}rd"},
    editor= {"Ek{\v{s}}tein, Kamil and P{\'a}rtl, Franti{\v{s}}ek and Konop{\'i}k, Miloslav"},
    title = {{"Advancing Hungarian Text Processing with HuSpaCy: Efficient and Accurate NLP Pipelines"}},
    booktitle = {{"Text, Speech, and Dialogue"}},
    year = "2023",
    publisher = {{"Springer Nature Switzerland"}},
    address = {{"Cham"}},
    pages = "58--69",
    isbn = "978-3-031-40498-6"
}

