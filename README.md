 
# Simple Generative AI App with Document Retrieval


This project demonstrates the creation of a simple generative AI application that can retrieve and process information from a webpage using OpenAI embeddings, vector databases (FAISS), and a retriever.

 

## Features
### Basic steps

1)Webpage Loader: Loads content from a given webpage URL.

2)Recursive Text Splitter: Splits the webpage content into manageable chunks for embedding.

3)OpenAI Embeddings: Transforms text chunks into vector embeddings for semantic search.

4)FAISS Vector Database: Stores the embeddings for efficient retrieval.

5)Retriever: Queries the vector database for relevant documents based on a user question.


### Running the App
After setting up the retriever and FAISS, you can run the app to retrieve relevant information from the webpage content. 

 ### Acknowledgements

OpenAI: This project uses the OpenAI GPT-4 API for generating embeddings and powering the language model. Thank you to OpenAI for providing access to their API.

LangChain: A big thanks to the LangChain team for providing an excellent framework for building LLM-powered applications and for enabling API tracking and tracing.

FAISS: Special thanks to the FAISS library for providing fast and efficient similarity search capabilities for the vector da

