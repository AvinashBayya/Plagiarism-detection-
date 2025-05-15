# Plagiarism-detection-
# Plagiarism Detection Project

## Project Overview

This project is a simple plagiarism detection tool that uses Natural Language Processing (NLP) techniques. It takes multiple text files as input and analyzes their content for similarity using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization and cosine similarity. This can help identify text documents that share similar content, indicating potential plagiarism.

## Features

* Reads text files from the project directory.
* Generates TF-IDF vectors for the text content.
* Calculates cosine similarity between documents.
* Detects and reports similar documents.
* Visualizes word clouds for document content (optional).

## File Structure

* **PLAG DETCT 2/juma.txt** - Sample text document.
* **PLAG DETCT 2/fatma.txt** - Sample text document.
* **PLAG DETCT 2/john.txt** - Sample text document.
* **PLAG DETCT 2/plagiarism.ipynb** - Main Jupyter Notebook for plagiarism detection.

## Requirements

* Python 3.x
* Jupyter Notebook
* Libraries:

  * numpy
  * matplotlib
  * scikit-learn
  * wordcloud

## Installation

1. Clone this repository or download the project files.
2. Make sure you have Python installed.
3. Install the required libraries using pip:

   ```bash
   pip install numpy matplotlib scikit-learn wordcloud
   ```
4. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook "PLAG DETCT 2/plagiarism.ipynb"
   ```

## Usage

* Open the Jupyter Notebook.
* Run each cell sequentially to:

  * Load and display the documents.
  * Vectorize the documents using TF-IDF.
  * Calculate cosine similarity between the documents.
  * Display similarity scores.

## How It Works

* TF-IDF is used to convert the text content of each document into numerical vectors.
* Cosine similarity is calculated between these vectors to determine the similarity between documents.
* A higher similarity score indicates a higher chance of plagiarism.

## Example Output

* Displays each document’s content.
* Shows similarity scores between documents.

## License

This project is licensed under the MIT License.
