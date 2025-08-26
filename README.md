# taha_week5
This project builds a Retrieval-Augmented Generation (RAG) system. Text data is embedded using SentenceTransformers and stored in a FAISS index for similarity search. When a user asks a question, the system retrieves the most relevant documents and passes them with the query to a language model (DistilGPT2), which generates a contextual answer.
