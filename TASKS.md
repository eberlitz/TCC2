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
    + atualizar metodologia
        + Atualizar do WordSimilarity para RG65/PT65, Talvez escrever o pq da mudança
    + experimentos 
        + Pegar meu artigo de como peguei os dados da Wikipedia
        + Descrever etapa de pre-processamento realizada no SEMANTICS 
        + Descrever a geração dos modelos, especialmente word2vecf
    + resultados
        + Explicar que o coeficiente pearson para WN é em relacao somente as palavras encontradas.
        + explicar em duas etapas os resultados obtidos 
            + quantitatico, 
            + qualitativo
    + Conclusão, trabalhos futuros
    + Atualizar o resumo
    + Atualizar o TITULO
    + ampliar o conceito de word embeding na fundamentação teorica
        + Falar sobre os vários tipos de word embeddings gerados (GloVe,FastText,word2vec,wang2vec,DEPS)
    + [Futuro] Vinculo experiemento do Denis


Background
    + Word Embeddings: GloVe,FastText,word2vec,wang2vec
    + WordNet Path Distance and Wu-Palmer similarity measures
    - Pearson’s Correlation ($\rho$)
Related work
    + DEPS
    - Artigo do Dataset PT65 - Granada
    - para portugues https://arxiv.org/pdf/1708.06025.pdf - Portuguese Word Embeddings: Evaluating on Word Analogies and
    Natural Language Tasks - NILC
    - BERT and ELMo
    - Pesquisar coisas novas
        - https://code.fb.com/ai-research/dynamic-meta-embeddings/
        - MultiLanguage
Evaluation
    - count the number of uniq words in the models to see if it is related to us having better results


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
