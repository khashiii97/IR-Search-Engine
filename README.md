# IR-Search-Engine
## Information retrieval course project
This Repository hosts the code of an search engine implemented as the project of our Modern Information Retrieval course project. <br/>
It supports both persian and english queries. The persian corpuses were obtained from farsi wikipedia pages, and the english were gathered from
TED talks which both rely in the data folder. <br/>

The implementation comprised of 4 stages:
- Preprocessing: which included Normalization, Tokenization, omitting punctuation symbols, Eliminating Stop Words, and Stemming
- Indexing: Positional and Bigram
- Compressing the Indexes: Gamma code and Variable Byte
- Mistake Correction : Using Bigram with Jaccard and Edit Distance

At the end, the engine was given queries based on tf-idf using InC-Itc
