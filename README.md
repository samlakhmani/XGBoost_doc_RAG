## Explanation 

This RAG project was built using Langchain

This is a rag which doloads all any documentation online, given the link 

Steps : 
1. Download all documentations
2. Make reasonable Chunks
     * Tricky bit was segregating code part of documentation, and providing adequate semantic meaning to it, for retrival of code
     * First version didnt have
     * The concept of perpozitionizer was used to add semantics to the purpose of the code 
4. Improve Chunk Calrity using : https://arxiv.org/abs/2312.06648 
5. Perform Embedding
6. Save in Chorma DB
7. Create Retrive using :
     * https://python.langchain.com/v0.1/docs/modules/data_connection/retrievers/MultiQueryRetriever/
     * https://python.langchain.com/v0.1/docs/modules/data_connection/retrievers/self_query/
7. Generate Response
   
