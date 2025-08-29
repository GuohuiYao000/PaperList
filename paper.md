# 自适应检索
* ACL2025 [SEAKR: Self-aware Knowledge Retrieval  for Adaptive Retrieval Augmented Generation](https://aclanthology.org/2025.acl-long.1312.pdf)
  在模型生成过程中，最后一位EOS符号的熵值可以代表模型对于生成结果不确定性的判断，因此[seakr](https://github.com/THU-KEG/SeaKR)提出了一种利用cot方法判断生成结果是否可信，进而决定是否检索的方法，该方法通过利用cot逐步检索生成结果，达到提升模型效果的作用         [seakr](pic/seakr.jpg)

# 查询增强
* ACL2025  [UniRAG: Unified Query Understanding Method for  Retrieval Augmented Generation](https://aclanthology.org/2025.acl-long.1456/)
  针对现阶段多种不同的查询增强方法，通过不同的查查询增强方法得到增强之后的查询，构建并过滤得到相关的训练数据集，通过不同的指令微调方式，1：利用对比学习训练大模型得到对应的查询增强方法以及增强后的查询；2：利用InfoNCE loss训练大模型，最相关的减速文档
  [nuirag](pic/UniRAG.jpg)

# 内部知识编辑





# 外部知识压缩



# RAG可解释性
* ACL2025  [VISA: Retrieval Augmented Generation with Visual Source Attribution](https://aclanthology.org/2025.acl-long.1456/)
  利用多模态输入，检索文档以图片形式，通过训练VLM模型，达到在图片中定位答案的目的，增加RAG的可解释性
