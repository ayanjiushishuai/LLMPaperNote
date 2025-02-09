# 
## 1. Question：Knowledge Conflict
> RAG might rely on imperfect retrieval results, including irrelevant, misleading, or even
 malicious information, which eventually leads to inaccurate LLM responses.

reason:
- corpus quality limitations
- reliability of retrievers
- complexity of the queries

### Imprefect reterival is common and harmful.
> – roughly 70% retrieved passages do not directly contain true answers, leading to the impeded performance of LLM with RAG augmentation.

20% of overall data have no mentions of the correct answer

### Imperfect retrieval leads to RAG failures
检索精度大于20%时，RAG能起到正向的作用;检索精度接近0时，RAG起到负向作用。

### Knowledge conflicts widely exist in RAG failures.
存在知识冲突时，LLM可能根据误导信息给出结论。

