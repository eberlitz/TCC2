https://www.semanticscholar.org/paper/Distributional-and-Knowledge-Based-Approaches-for-Oliveira/1dc0e1d1d84d266adbcc0a8b468630dbd9a349aa






Todo

aims to improve the accuracy and recall of these terms ex-pansion through the use of word embeddings

- 2 No abstract e resumo, reforçar a contribuição do teu sistema.
- 10 Reforçe as contribuições na conclusão.

Questions
- Artigo semelhante
- 3 No 1.1 - Motivation, seria bacana trazer mais referencias, pois mostras que o teu trabalho é muito relevante e nao tem ainda no mundo. - Não acho que seja necessário, eu considerei como motivação o que me motivou a realizar o trabalho, e no topico seguinte eu descreve o problema de pesquisa, talvez estes dois topicos separados gerou confusão.
- 4 No 1.2 - Research problem, nao esta claro o teu research problem. Seria bacana coloca-lo em um itemize. Eu coloquei em itemize os meus objetivos pra ficar claro. Nao sei se não é apenas confusão dos topicos
- 5 Qual seria a diferença entre o 1.2 e 1.3 - Research focus? O 1.3 seriam os objetivos? - confusao?

Can't do
- 7 No 3.5 - Discussions, seria possível gerar alguma tabela comparativa, mostrando claramente a lacuna na área.} - Não consigo em virtude de não ter o que comparar pois sao trabalhos que fornecem a base para o meu trabalho. Relação vertical e nao horizontal.

Optional
- 1 Colocaria os parágrafos um pouco maiores. 10 linhas por exemplo.}
- Incluir natureza e tipo de pesquisa

Done
+v6 Imagem demonstrando one-hot and feature vectors
+v6 8 O core do teu trabalho seria o 4.1 - Methodology overview, certo? Deves deixar mais claro o que é teu, o que é legado dos outros e reforçar muito o que voce fez. Poderias sinalizar na figura 2 o que 'e teu, ou seja, a tuia adição na literatura.
+v6 Citar o trabalho semelhante na parte de introdução, quando comenta sobre trabalhos existentesm tendências, etc. Veja qual considera o melhor ponto e faça a inserçào.
+v6 Adicionar uma ou mais referências alem de Agirre2009 sobre o uso de abordagens distribucionais para cobrir out-of-vocabulary terms in WordNet
+v6 11 E quais são as limitações de teu trabalho?
+v6 6 1.4 NAO é estrutura da thesis e sim do documento}
+v6 9 Na tabela 2, por exemplo, tem coisas me negrito. Deves sinalizar no caption o que é esse negrito.}
+ 12 Referencias ok. Cuide os S.l. e s.n.: [LaTeX NAO PERMITE É PARTE DA ABNT]
+v5 Subsection 3.5 discussions com as conclusões de cada trabalho relacionado


\citetext{wazlawick2017metodologia}
\citetext{gil2002elaborar}
\citetext{koche2016fundamentos}


//-----------------------------------------------------------------








Title
    - Portuguese Word Embeddings: Evaluating on word similarity
Background
    + Word Embeddings: GloVe,FastText,word2vec,wang2vec
    + WordNet Path Distance and Wu-Palmer similarity measures
    - Pearson’s Correlation ($\rho$)
Related work
    + DEPS
    + Artigo do Dataset PT65 - Granada
    + para portugues https://arxiv.org/pdf/1708.06025.pdf - Portuguese Word Embeddings: Evaluating on Word Analogies and
    Natural Language Tasks - NILC
    + BERT and ELMo
    - Verificar se "A study on similarity and relatedness using distributional and WordNet-based approaches" tem alguma relação com meu trabalho.
    - Pesquisar coisas novas
        - https://code.fb.com/ai-research/dynamic-meta-embeddings/
        - MultiLanguage
Methods and materials
    - natureza e abordagem metodologica essas coisas 
Evaluation
    + count the number of uniq words in the models to see if it is related to us having better results
    + [IMPORTANT]Posso ter errado o tipo de avaliacao We use Pearson (r) and Spearman (ρ) correlation

//---------
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



