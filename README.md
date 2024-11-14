In this business use case with Generative AI, time series data from the financial  markets will be analyzed in conjunction with the quarterly reports on the company’s performance. The daily price movements for a stock, such as Micron, will be ingested and  transformed through technical indicator analysis. The quarterly earnings report will be queried by an open source LLM, such as Mistral AI, based on the input prompt. Retrieval augmented generation will be implemented to parse and store the document in an open source VectorDB, such as ChromaDB. The LLM response will be merged with the transformed market data for storage as a data object or in a data lakehouse for further user driven analysis

Installation of Packages for Generative AI & Technical Analysis

# Install the main packages
pip install langchain

pip install -U langchain-community

pip install langchain-mistralai

pip install chromadb

pip install mistralai
