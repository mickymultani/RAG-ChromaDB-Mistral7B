# RAG-ChromaDB-Mistral7B
RAG (Retrievel Augmented Generation) implementation using ChromaDB, Mistral-7B-Instruct-v0.1 and gte-base for embeddings.

# RAG Implementation with Mistral 7B and ChromaDB: Readme

## Project Description
This repository hosts the implementation of a sophisticated Retrieval Augmented Generation (RAG) model, leveraging the cutting-edge Mistral 7B model for Language Generation. It utilizes the gte-base model for embedding and ChromaDB as the vector database to store these embeddings. This project is embodied in a Google Colab notebook, fine-tuned for an A100 instance.

The implementation queries data from the “Climate Change 2023 Synthesis Report,” allowing for the extraction of in-depth, coherent, and relevant information pertaining to climate change. With a context window of 8000, the results demonstrate impressive coherence, precise data match-retrieval, and low latency, making it a valuable tool for processing extensive datasets.

## Contents
- `RAG_Chromadb_mistral7b.ipynb` : The main Google Colab notebook containing the complete implementation and execution details.

## Prerequisites
- Google Colab with A100 instance.
- Familiarity with RAG, gte-base model, Mistral 7B, and ChromaDB.

## Quick Start
1. Clone the repository:
   ```shell
   git clone https://github.com/mickymult/RAG-ChromaDB-Mistral7B.git
   ```
2. Open the `RAG_Chromadb_mistral7b.ipynb` notebook in Google Colab.
3. Set up the environment with the necessary libraries and dependencies.
4. Run the notebook cells in sequence.

## Implementation Details
### 1. **Mistral-7B-Instruct-v0.1 (LLM)**
   Mistral 7B serves as the foundational Language Model, producing coherent, contextually relevant responses based on retrieved documents.

### 2. **gte-base Model (Embedding Model)**
   The gte-base model is used for embedding sentences, which facilitates efficient and semantically rich similarity search among them.

### 3. **ChromaDB (Vector Database)**
   ChromaDB is used as the vector database for storing the embedded representations of the data, ensuring efficient data retrieval.

### 4. **Data Source**
   The implementation is based on the “Climate Change 2023 Synthesis Report,” enabling detailed inquiry into the comprehensive insights on climate change covered in the report.

### 5. **Enhanced Context Window**
   The context window has been increased to 8000 tokens to allow for more extensive contextual understanding and coherence in the generated responses.

## Results
The implementation yields highly coherent responses with accurate data match-retrieval and minimal latency, demonstrating its effectiveness in handling extensive and complex datasets like the Climate Change 2023 Synthesis Report.

## Usage
Execute the implementation by running the cells in sequence in the `RAG_Chromadb_mistral7b.ipynb` notebook on Google Colab.

## Contribution
Feel free to contribute to the enhancement of this implementation. 

## License
This project is distributed under the MIT License. 

## Acknowledgments
- Mistral 7B for providing the advanced language model.
- gte-base for the robust embedding model.
- ChromaDB for efficient vector database storage.
- The authors and contributors to the Climate Change 2023 Synthesis Report.

## Contact
For any inquiries, discussions, or clarifications related to this implementation, please create an issue in this GitHub repository.
