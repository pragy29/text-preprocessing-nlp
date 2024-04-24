# Patent Grant Analysis and Text Pre-Processing

## Overview
This project focuses on two key areas:
1. **Parsing Patent Grants**: Extracting information from semi-structured text files and saving it in CSV and JSON formats.
2. **Text Pre-Processing**: Converting text data into a numerical format for NLP applications and generating statistics.

## Key Features

### Patent Grants Parsing
- Parses text data containing patent grant information.
- Extracts attributes such as grant ID, patent kind, patent title, number of claims, citations, inventors, and abstract.
- Outputs the parsed data to CSV and JSON files for further analysis.

### Text Pre-Processing
- Processes a set of published papers to create a sparse representation of their content.
- Generates a vocabulary index and sparse count vectors for further analysis.
- Provides a CSV file with statistics, such as the top 10 most frequent terms in titles, abstracts, and author names.

### Setup and Prerequisites
- **Python 3.x**: Ensure you have Python installed on your system.
- **Jupyter Notebook**: To run the provided notebooks.
- **Required Libraries**: Install the following packages:
```sh
pip install pandas pdfminer.six nltk
```

### Running the Project
- Open the Jupyter notebooks (task1_31940757.ipynb, task2_31940757.ipynb) in Jupyter Notebook or Google Colab.
- Run the code to parse the text files and perform text pre-processing.
- Check the generated data to ensure proper output.

### Input Files
- Patent Grant Data: Contains information about patent grants, including grant IDs, titles, claims, citations, inventors, and abstracts.
- Paper URLs: A PDF file containing a list of URLs for papers published in a popular AI conference.

### Repository Structure
- task1_31940757.ipynb: Notebook for parsing patent grant data.
- task2_31940757.ipynb: Notebook for text pre-processing and generating statistics.

### Authors
- [Pragy Parashar](https://github.com/pragy29)
