# financial_wizard


# Retrieval-Augmented Summary

- **Pinecone** for vector storage & similarity search  
- **Cohere** for text embeddings  
- **Hugging Face** (Flan-T5) as a free local LLM  --- need to update this to use fin-R1
- **LangChain** to wire everything together  

touch .env and replace your keys

MISTRAL_API_KEY="" # mistral api key <br>
COHERE_API_KEY="" # cohere api key <br>
PINECONE_API_KEY = "" # pinecone api key <br>
PINECONE_ENVIRONMENT='us-east-1' # pinecone environment <br>
INDEX_NAME = "financial-wizard" # pinecone index name <br>