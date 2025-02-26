> ## Natural Language Processing: Aplicação de Técnicas de NLP a Canais de Atendimento

> ### Qual o contexto ?
- A QuantumFinance tem um canal de atendimento via chat e precisar classificar os assuntos dos atendimentos para melhorar as tratativas dos chamados dos clientes. O canal recebe textos abertos dos clientes relatando o problema e/ou dúvida e depois é direcionado para algum uma área especialista no assunto para uma melhor tratativa.​

> ### Qual o desafio ?
- Crie um modelo classificador de assuntos aplicando técnicas de NLP, que consiga classificar através de um texto o assunto conforme disponível na base de dados [1] para treinamento e validação do seu modelo.​ O modelo precisar atingir um score na métrica F1 Score superior a 75%. Utilize o dataset [1] para treinar e testar o modelo, separe o dataset em duas amostras (75% para treinamento e 25% para teste com o random_state igual a 42).​ Lembre-se de utilizar ao menos uma aplicação de modelos de GenAI (LLM´s) para criar o modelo classificador com os mesmos critérios do item anterior.

> ### Quais as contribuições do projeto para o meu desenvolvimento ?
- Pré-processamento de textos para facilitar a interpretação dos dados.
- Remoção de stop words utilizando as bibliotecas NLTK e Spacy.
- Técnicas de vetorização como Count Vectorizer, TF e TF-IDF.
- Lemmatização para alterar todas as palavras para os seus radicais.
- Classificação utilizando Decision Tree, Logistic Regression e Support Vector Machine.
- Uso da API da OpenAI para classificação usando os modelos GPT-4, GPT-4o-Mini e GPT-3.5-Turbo e Sabia-3.