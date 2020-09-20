# KnowledgeGraph

This repository aims to store the knowledge graph related paper.

1. **TransE: Translating Embeddings for Modeling Multi-relational Data.**
*Antoine Bordes, Nicolas Usunier, Alberto Garcia-Duran, Jason Weston, Oksana Yakhnenko.*  NIPS 2013. [paper](http://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data.pdf) [code](https://github.com/thunlp/OpenKE) [explaination](http://pyvandenbussche.info/2017/translating-embeddings-transe/#:~:text=TransE%20is%20a%20method%20which,of%20the%20knowledge%20graph%20entities.)
	> TransE is the first model to introduce translation-based embedding, which interprets relations as the translations operating on entities.
	> It inspired from the work of Tomas Mikolov: word2vec.
	
1. **TransH: Knowledge Graph Embedding by Translating on Hyperplanes.**
*Zhen Wang, Jianwen Zhang, Jianlin Feng, Zheng Chen.* AAAI 2014. [paper](http://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/viewFile/8531/8546) [code](https://github.com/thunlp/OpenkE)
	> To preserve the mapping propertities of 1-N/N-1/N-N relations, TransH inperprets a relation as a translating operation on a hyperplane. In addition, TransH proposes "bern.", a strategy of constructing negative labels.

1. **TransR & CTransR: Learning Entity and Relation Embeddings for Knowledge Graph Completion.**
*Yankai Lin, Zhiyuan Liu, Maosong Sun, Yang Liu, Xuan Zhu.* AAAI 2015. [paper](http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/download/9571/9523/) [KB2E](https://github.com/thunlp/KB2E) [OpenKE](https://github.com/thunlp/OpenKE)
	> An entity may have multiple aspects and various relations may focus on different aspects of entites. TransR first projects entities from entity space to corresponding relation space and then builds translations between projected entities.
	CTransR extends TransR by clustering diverse head-tail entity pairs into groups and learning distinct relation vectors for each group, which is the initial exploration for modeling internal correlations within each relation type.

### Must-read papers on Graph Neural Network from thunlp
https://github.com/thunlp/GNNPapers#knowledge-graph

### Must-read papers on KRL/KE from thunlp
https://github.com/thunlp/KRLPapers/blob/master/README.md

### Awesome Knowledge Graph Embedding Approaches from mommi84
https://gist.github.com/mommi84/07f7c044fa18aaaa7b5133230207d8d4

### Dynamic Knowledge Graph Completion from woojeongjin
https://github.com/woojeongjin/dynamic-KG

### Quert2box
http://snap.stanford.edu/query2box/
