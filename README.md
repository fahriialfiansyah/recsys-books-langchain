# Chat with Multiple PDF Using LangChain, Ollama, and Llama3 8B
Dataset Source: https://www.kaggle.com/datasets/luiscorter/netflix-original-films-imdb-scores
This project creates recommender system local interfaces for single csv dataset using LangChain, Ollama, and the LLaMA 3 8B model. The repository includes sample csv, notebook, and requirements for interacting with and make a recommendation about movies based on previous watched movie. It uses Python 3.12.4 and [kaggle dataset](https://www.kaggle.com/datasets/luiscorter/netflix-original-films-imdb-scores) as knowledge database.

## File Information
[notebook-1.ipynb](https://github.com/fahriialfiansyah/recsys-movies-langchain/blob/main/notebook-1.ipynb):
- Vector database: FAISS
- LLM: Llama3-8B
- Embedding: Llama3-8B

[notebook-2.ipynb](https://github.com/fahriialfiansyah/recsys-movies-langchain/blob/main/notebook-2.ipynb):
- Vector database: FAISS
- LLM: Llama3-8B
- Embedding: all-MiniLM-L6-v2

## Installation Steps
1. Clone the repository:
```shell
git clone https://github.com/fahriialfiansyah/recsys-movies-langchain.git
```
2. Navigate to the project directory:
```shell
cd recsys-movies-langchain
```
3. This project uses [Pip Python](https://pip.pypa.io/en/stable/) for dependency management. Install the required dependencies:
```shell
# create python environment
python -m venv .venv

# activate the virtual environment
.venv/Scripts/activate

# install the dependencies
pip install -r requirements.txt
```
4. Download Ollama from https://ollama.com and follow their installation instructions.
5. Open terminal to install Llama3:8B LLM Model:
```shell
ollama pull llama3:8b
```
6. Run the recommender system code locally.
