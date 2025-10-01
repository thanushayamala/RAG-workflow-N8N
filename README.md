# RAG-workflow-N8N
RAG Workflow: Google Drive → Vector DB Q&amp;A  Automates RAG ingestion: Google Drive file uploads are chunked, embedded via OpenAI, and stored in Pinecone. A separate trigger handles queries; an AI Agent uses Pinecone retrieval to ground responses from the OpenRouter Chat Model.
