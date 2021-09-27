## pytorch

- [python文本分析之处理和理解文本](https://zhuanlan.zhihu.com/p/340879728)

### [Embedding](https://towardsdatascience.com/neural-network-embeddings-explained-4d028e6f0526) or (https://zhuanlan.zhihu.com/p/46016518)

Embedding:一种将**离散变量**转变为**连续向量**的方式

One-hot 编码两大缺点

- 对于具有非常多类型的类别变量，变换后的向量维数过于巨大，且过于稀疏。
- 映射之间完全独立，并不能表示出不同类别之间的关系。

### [Word2vec](https://code.google.com/archive/p/word2vec/)

The word2vec tool takes a **text corpus** as input and produces the **word vectors** as output

two main learning algorithms:
- [bag-of-words](https://arxiv.org/pdf/1301.3781.pdf)
- [skip-gram](https://arxiv.org/pdf/1310.4546.pdf)