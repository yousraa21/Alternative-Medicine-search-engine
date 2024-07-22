# Alternative-Medicine-search-engine
This project contains a Python script (gui.py) for a graphical user interface (GUI) that performs search and query expansion on a dataset related to alternative medicine. The GUI was generated using Tkinter Designer by Parth Jadhav.
Features

    Search Functionality: Allows users to search the dataset using boolean and TF-IDF based queries.
    Query Expansion: Expands user queries by extracting relevant terms from top-ranked documents.
    Results Display: Displays the search results within the GUI.
    Preprocessing: Preprocesses the dataset for effective searching.
    Inverted Index Creation: Builds an inverted index for efficient query processing.
    Weight Calculation: Calculates weights (TF-IDF scores) for terms in the dataset.
    Requirements

    Python 3.x
    Tkinter
    NLTK

You can install the necessary packages using pip:```pip install nltk```
How to Run

    1 Clone this repository:```git clone https://github.com/yourusername/your-repo-name.git```
    2 Navigate to the project directory: ```cd your-repo-name```
    3 Run the GUI script: ```python gui.py```
Files

    gui.py: The main script for the GUI.
    preprocessing+inverted index+weight: Script for preprocessing the dataset+Script for creating the inverted index+Script      for calculating term weights (TF-IDF).
    tfidf-result.txt: File containing TF-IDF scores for terms.
    processed_documents.txt: File containing preprocessed documents.
    inverted-index.json: File containing the inverted index of the dataset.
    DATA-OF-ALTERNATIVE-MEDICINE-1.txt: The dataset file.

Usage

    Search: Enter your query in the search box and click the "Search" button.
    Query Expansion: The expanded query functionality can be triggered by clicking the respective button.
    Results: The search results are displayed in the text widget area of the GUI.
Functions
Main Functions

    preprocess_text: Preprocesses the input text (tokenization, normalization, stopword removal, stemming).
    load_inverted_index: Loads the inverted index from a JSON file.
    calculate_tfidf_for_query: Calculates the TF-IDF scores for the query terms.
    calculate_document_scores: Calculates similarity scores for each document based on TF-IDF scores.
    rank_documents: Ranks documents based on cosine similarity scores.
    boolean_search: Performs a boolean search on the dataset.
    read_documents: Reads the dataset and stores it in a dictionary.
    on_button_click: Callback function for the search button.
    expand_query: Expands the user's query using top-ranked documents.



GUI Elements

    Entry Widget: For user to input search queries.
    Button Widget: To initiate search and query expansion.
    Text Widget: To display search results.
    Canvas: To layout and design the GUI elements.
