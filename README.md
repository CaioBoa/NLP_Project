# Análise de Afinidade Artística por Época com NLP e Machine Learning

Este projeto investiga a relação entre artistas musicais e as décadas em que atuaram, utilizando técnicas de **Processamento de Linguagem Natural (NLP)** e **Machine Learning** para mensurar:

- **Afinidade com a época** com base em características musicais e letras.
- **Sentimento e estilo lírico** predominante em diferentes períodos.
- **Comparações entre artistas de uma mesma década.**

## Objetivos

- Entender qual o sentimento e contexto sociocultural foi transmitido em cada década da música
- Analisar quais artistas mais se distanciavam do contexto de sua época e quais artistas mais abraçavam esse contexto
- Conceder uma resposta para a pergunta: A música do nosso século é apenas produto mídiatico?

## Estrutura do Projeto

- `Project.ipynb`: Notebook principal contendo a coleta, pré-processamento, análise e visualizações.
- `BagOfWords.ipynb`: Protótipo inicial exploratório que testa modelos simples de predição de década com base em Bag of Words.

> Necessário um arquivo .env com: GEMINI_API_KEY, SPOTIFY_SECRET, SPOTIFY_CLIENT_ID
