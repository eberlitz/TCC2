+ Procurar artigo que descrevia como avialiar qualitativamente
    - Dependency-Based Word Embeddings

+ [CONCLUÍDO]Realizar experiementos
    + quantitativo sobre o dataset PT65 (tive que mudar de dataset, antes era o WordSimilarity353): 
        + Sobre os meus modelos gerados: Criar um programa para fazer a avaliação
        + Sobre os modelos do NILC
    + qualitativo: Comparar os modelos pegando as top palavras mais semelhantes
- Escrever artigo:
    + [FAZENDO ESTA SEMANA] Escrever um resumo de como 
    realizei os experiementos com a nova arquitetura
     e resultados obtidos e 
     marcar uma reunião com o Sandro. 
     (resumo será parte da metodologia e 
     analise de resultados do artigo)
    - Texto do artigo
        + atualizar metodologia
            + Atualizar do WordSimilarity para RG65/PT65, Talvez escrever o pq da mudança
        - experimentos 
            + Pegar meu artigo de como peguei os dados da Wikipedia
            - Descrever etapa de pre-processamento realizada no SEMANTICS 
            - Descrever a geração dos modelos, especialmente word2vecf
        - resultados
            - explicar em duas etapas os resultados obtidos ( quantitatico, qualitativo )
            - Explicar que o coeficiente pearson para WN é em relacao somente as palavras encontradas.
        - Conclusão, trabalhos futuros
        - ampliar o conceito de wordembeding
            - Falar sobre os vários tipos de word embeddings gerados (GloVe,FastText,word2vec,wang2vec,DEPS)
        - atualizar trabalhos relacionados
            - Artigo do Dataset PT65
            - para portugues https://arxiv.org/pdf/1708.06025.pdf
            - Pesquisar coisas novas
                - https://code.fb.com/ai-research/dynamic-meta-embeddings/
                - MultiLanguage
- [Futuro] Vinculo experiemento do Denis


Tools
+ Open Multilingual Wordnet
+ Python3.6
+ NLTK
+ PALAVRAS Parser
+ FastText
+ Wang2vec
+ Word2vec
+ GloVe
+ DEPS - Word2vecf
+ PT65 dataset
+ NILC pre-trained word embeddings
+ semantics.unisinos.br computer with 32 cores
+ Docker
- Gensim Word2vec


+ Corpus generation
1. wikipedia PT-BR dump
1. preprocessing with wikiextractor
1. preprossesing sentence tokenizer plus few things

PALAVRAS Annotaded corpus generation
1. converted sentences to a sqlite to be able to recover progress of palavras parser in case of errors
1. python code to run the PALAVRAS Parser in multiple cores to reduce from 14 days to 24 hours
Common Word Embeddings generation
1. GloVe,FastText,word2vec,wang2vec model generations
DEPS Word Embedding generation
1. script to generate word2vecf(DEPS) input files from the palavras anotated sentences
1. deps model generation

WordNet evaluation
1. script to quantitative evaluate two WordNet similarity metrics (Wu-Palmer and Path-distance) against the PT65 dataset
Word embeddings Evaluation
1. script to quantitative evaluate all models against the PT65 dataset
1. script to query the top most similar words to a given set of target words for manual qualitative evaluation.
1. script to download all NILC pre-trained word embeddings and quantitative evaluate all models against the PT65 dataset
