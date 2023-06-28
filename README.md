# pdfNEETbot
![Logo]([img/"The Crest Logo"](https://github.com/Anandharajan/pdfNEETbot/blob/main/img/The%20Crest%20Logo.jpg))


**Try the app here:** [pdfNEETbot on Streamlit Cloud](https://apppy-xfmcjly1ifm.streamlit.app/)

# pdfNEETbot

Its a bot used to browse through texts given by students to prepare for NEET and explore answers for the certain topics.

## Features

Document Upload: The PDF bot allows users to upload PDF or TXT documents for processing and analysis.

Retrieval Methods: The bot offers two retrieval methods: Similarity Search and Support Vector Machines. Users can choose the method that suits their needs.

Similarity Search: This retrieval method compares the uploaded documents with a knowledge base to find similar documents. It employs techniques like semantic similarity and word embeddings to determine document relevance.

Support Vector Machines: The bot utilizes Support Vector Machines (SVM) for retrieval. SVM is a machine learning algorithm that classifies documents based on their features and can be used to find relevant documents.

Sample Question-Answer Pairs: The bot generates sample question-answer pairs based on the content of the uploaded documents. These pairs can serve as examples for understanding the document's information and structure.

Document-Related Questions: Users can ask questions related to the content of the uploaded documents. The bot uses its retrieval methods to find the most relevant answers.

Answer Retrieval: Based on the selected retrieval method, the bot retrieves answers from the knowledge base or uses SVM to classify and provide relevant answers to user queries.

## Installation

Clone this repository:

```bash
git clone https://github.com/Anandharjan/pdfNEETbot.git
cd pdfNEETbot
```

Create a virtual environment and install the required packages:

```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## Usage
To run the app, simply execute the following command:

```bash
streamlit run qa_app.py
```

After running the command, you can access the app through your web browser using the provided URL.

Developed by [Anandharajan](https://twitter.com/trvanand)
