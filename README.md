# RAG-with-LLMs
RAG with LLMs
### 主要的RAG步骤有：
1. 载入文档
2. 数据预处理：文档切分成chunks，编码成embeddings，存储到vectorstore (Chroma)
3. 文档问答任务

### 主要用到的方法：
* CoT prompting
* Query Transformation (Rewrite-Retrieve-Read)
