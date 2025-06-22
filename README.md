# Plagiarism-Checker
Definition
- Plagiarism Checker is a Python-based tool used to compare two or more textual documents and determine how similar they are. It helps detect potential cases of plagiarism by calculating the cosine similarity between documents using Natural Language Processing (NLP) techniques.
- It can be used by students, educators, and writers to compare documents and identify potential plagiarism by analyzing textual overlaps and computing similarity scores.

## Features
- Compare two or more text documents for similarity
- Detect matching or near-matching sentences
- Generate a similarity percentage score
- Simple CLI-based interface
- Works offline — no internet required

## Libraries Used:
- `sklearn` – for cosine similarity

## How It Works
- Load and clean the text files or inputs
- Tokenize and vectorize the text using `TfidfVectorizer`
- Calculate the cosine similarity between the documents
- Output a percentage score representing text similarity

### Steps to Achieve This
- Prepare Your Text Files
  - Place two text files (e.g., `doc1.txt` and `doc2.txt`) in your project folder. These will be compared.
- Use TF-IDF Vectorization
  - Use `TfidfVectorizer` to convert the raw text into numerical vectors that represent the importance of words.
- Calculate Cosine Similarity
  - Use `cosine_similarity` to calculate how close the documents are in terms of content.


## Install Dependencies
- ````
  pip install scikit-learn nltk
  ````

## Project Structure
![image](https://github.com/user-attachments/assets/affe84e2-8fce-46c4-9355-a25237c4a355)


## Steps to Run
- ### Clone the Repository
````
git clone https://github.com/CodeCrafter-101/plagiarism-checker.git
cd Plagiarism-Checker
````
- ### Import necessary modules
- ### Place or Write Your Text Files
- - Make sure you have `doc1.txt` and `doc2.txt` in the same folder (or change the filenames accordingly).
- ### Run the Script
````
python plagiarism_checker.py
````



