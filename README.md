# LLM_Class_Projects

A collection of projects exploring Large Language Models (LLMs) in music analysis, theory, and related applications.

## Notebooks

- **A_LLM_LangChain_Intro.ipynb**: Introduction to Large Language Models and the LangChain framework.
- **B_Concert_Programs_LLM/13_Haverford_Concerts_LLM.ipynb**: Analysis of Haverford concert programs using LLMs.
- **C_Theory_LLM.ipynb**: Theoretical aspects of Large Language Models. Note: The Chroma database for this notebook is stored separately in the `chroma_files/` directory.
- **D_Music_Analysis_LLM.ipynb**: Music analysis using Large Language Models.
- **E_Vaudeville_Structured_LLM/15_Vaudeville_LLM.ipynb**: Structured analysis of Vaudeville materials with LLMs.

## Data Files

- `english_html_metadata.csv`: Metadata for English HTML documents.
- `music_summaries.json`: Summaries of music-related content.
- `MEI Sample/`: Sample Music Encoding Initiative (MEI) files including works by Bach, Bartók, and Morley.

## Required Libraries

The notebooks require the following Python libraries (install via `pip install`):

- langchain
- langchain-openai
- langchain-chroma
- langchain-core
- langchain-community
- langchain-experimental
- langgraph
- pandas
- chromadb
- music21 (for D_Music_Analysis_LLM.ipynb)
- reportlab (for C_Theory_LLM.ipynb)
- pydantic (for E_Vaudeville_Structured_LLM.ipynb)
- openai

You will also need an OpenAI API key set as an environment variable `OPENAI_API_KEY`.

## Installation

To install locally:

```bash
# clones all documents and folders
git clone https://github.com/RichardFreedman/LLM_Class_Projects.git
# now cd to the concert programs
cd LLM_Class_Projects/B_Concert_Programs_LLM/
# and pull the large chroma db
git lfs pull
```

## Usage

Open the respective Jupyter notebooks in a Jupyter environment to explore the analyses and run the code.
