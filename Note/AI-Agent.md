# AI-Agent
## 九、十
1. Example
   - AutoGPT
   - AgentGPT
   - BabyAGI
2. Transformer
   - Tokenization
   - Input  Layer
   - Block{
   - Attention 
   - Feed  Forward
   - }
   - Output  Layer
----
1. Tokenization  
   - Token   List(Byte Pair Encoding)   
   - Embedding with Cluster Classification
       - Defect: Embedding ignores the Context
2. Positional Embedding as parameter
{
3. Attention
   - Contextualized Embedding
   - Attention Weight
   - Mask the later one
   - **Multihead Head**
   - Weight Sum
4. Feed Forward
} Transformer Block --> Layer
5. Output Layer{Linear Block + SoftMax}==FNN
##### Hint: why mask the later ones
1. Information Leaky
2.  Hash Rate Lack