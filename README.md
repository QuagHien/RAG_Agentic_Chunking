## Agentic chunking strategy in Retrieval-Augmented Generation (RAG)

 A Retrieval-Augmented Generation (RAG) system built upon the Agentic Chunking Strategy. The system enables users to upload, chunk, and store PDF documents in a Qdrant vector store. It facilitates efficient document processing and retrieval by breaking down large files into manageable chunks. Users can then query the system with questions related to the uploaded documents, and the system will provide the most accurate and relevant answers by leveraging the chunked information from the vector store.
## Quick Start
```
git clone https://github.com/QuagHien/RAG_Agentic_Chunking.git
python3 RAG_Agentic_Chunking/src/demo_rag.py
```

Architecture:

<img src="https://github.com/QuagHien/RAG_Agentic_Chunking/blob/main/images/RAG%20architecture.png" alt="rag" />

## Agentic Chunking Strategy
<img src="https://github.com/QuagHien/RAG_Agentic_Chunking/blob/main/images/agentic%20chunking.png" alt="chunking" />
<img src="https://github.com/QuagHien/RAG_Agentic_Chunking/blob/main/images/Flow%20of%20Agentic%20Chunking.png" alt="flow" />

Run Agentic Chunking Strategy in: RAG_Agentic_Chunking/examples/Agentic_Chunking_LAMMA3_1.ipynb
 
