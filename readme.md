# Repositório: Processamento de Linguagem Natural (PLN)

Este repositório contém as listas de exercícios desenvolvidas para a disciplina de Processamento de Linguagem Natural do Instituto de Computação (IC) da Universidade Federal de Alagoas (UFAL).

## Visão Geral

Os notebooks e scripts cobrem uma variedade de tópicos fundamentais e avançados em PLN, desde o processamento básico de texto até o uso de modelos de transformadores e LLMs.

### Conteúdo das Listas

O repositório está organizado nas seguintes listas de exercícios:

* **Lista 1 (`/lista1`)**:
    * Fundamentos de processamento de texto.
    * Uso de Expressões Regulares (Regex) para validação (senhas, e-mails) e extração de padrões (citações APA).
    * Tokenização, remoção de stopwords, stemming e etiquetagem POS (Part-of-Speech) com NLTK.

* **Lista 2 (`/lista2`)**:
    * Classificação de sentimentos (Positivo, Negativo, Neutro) utilizando abordagens Bag-of-Words (CountVectorizer, TF-IDF).
    * Comparação de classificadores clássicos (Regressão Logística, Naive Bayes, SVM).
    * Modelagem de Tópicos (NMF e BERTopic).
    * Agrupamento de dados (K-Means) e visualização (t-SNE, UMAP).

* **Lista 3 (`/lista3`)**:
    * Embeddings de palavras (Glove e Word2Vec) para busca de similaridade.
    * Classificação de texto usando Doc2Vec e modelos de redes neurais (LSTM).
    * Análise de texto com spaCy: Reconhecimento de Entidades Nomeadas (NER), etiquetagem POS e análise de grafos de coocorrência (NetworkX).
    * Tradução automática (Inglês-Português) usando um modelo Sequence-to-Sequence (Seq2Seq) com Keras.

* **Lista 4 (`/lista4`)**:
    * Classificação de texto utilizando modelos Transformers (Sentence Transformers com DistilBERT).
    * Implementação de um bloco Transformer customizado em Keras/TensorFlow para classificação.
    * Interação com Modelos de Linguagem de Larga Escala (LLMs) usando Ollama (Llama 3.1) para extração de entidades.

## Como Executar

Para executar os notebooks e scripts deste repositório, é recomendado criar um ambiente virtual e instalar as dependências listadas.

1.  Clone o repositório:
    ```bash
    git clone https://github.com/luizwhirl/Natural-Language-Processing.git
    cd natural-language-processing
    ```

2.  Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

3.  Execute os notebooks Jupyter ou os scripts Python.
