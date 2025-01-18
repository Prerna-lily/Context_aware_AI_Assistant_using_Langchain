**Context Aware AI Assistant**

The project provides a complete pipeline for semantic text search and comparison using OpenAI embeddings. 
It demonstrates how to generate vector representations of words and documents, store them in a vector database, and perform efficient similarity-based retrieval for real-time question-answering.

 Now run this command to install dependenies in the `requirements.txt` file. 

```python
pip install -r requirements.txt
```

3. Install markdown depenendies with: 

```python
pip install "unstructured[md]"
```

## Create database

Create the Chroma DB.

```python
python create_database.py
```

## Query the database

Query the Chroma DB.

```python
python query_data.py "How does Alice meet the Mad Hatter?"
python query_data.py "What is the Cheshire Cat's advice to Alice?"
```
You'll also need to set up an OpenAI account (and set the OpenAI key in your environment variable) for this to work.
