# rag-tutorial-v2

This repository is a starter guide for learning how to use Retrieval-Augmented Generation (RAG) with Ollama. Follow the steps below to set up and run the project.

## Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- pip (Python package installer)

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd rag-tutorial-v2
    ```

2. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

## Setting Up the Database

1. Place your PDF documents in the [data](data) directory.

2. Populate the database with the documents:
    ```sh
    python populate_database.py --reset
    ```

## Querying the Database

To query the database, run the [query_data.py](query_data.py) script with your query text:
```sh
python query_data.py "Your query text here"
```
## Project Structure

```github.io(rag-tutorial-v2)
|- rag-tutorial-v2/
|  |- chroma
|  |- data
|  |- LICNESE
|  |- README.md
|  |- requirements.txt
|  |- ......
```
