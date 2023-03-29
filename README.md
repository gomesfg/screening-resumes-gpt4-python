# Triagem de currículos utilizando GPT-4

## Índice <a name="index"></a>

- [Pré-requisitos](#installation)
- [Introdução](#introduction)
- [Desenvolvimento](#development)
- [Licença](#license)

## Pré-requisitos <a name="installation"></a>

[(Voltar ao topo)](#index)

- Possuir uma conta Google;
- API Key para executar a API REST do OpenAI (deve ser configurada dentro do notebook).

## Introdução <a name="introduction"></a>

[(Voltar ao topo)](#index)

- Os modelos GPT vem demonstrando habilidade excepcional em responder questões com base em informações disponíveis na web, em livros e na vasta gama de fontes usados para treiná-los. Neste projeto, a proposta é desenvolver um modelo utilizando as habilidades de pergunta e resposta do GPT-4, para resolver um problema da triagem de currículos.

- Mas porque desenvolver um modelo de triagem de curriculos? 
O principal problema que os algoritmos enfrentavam até então, era a falta de padronização e informação nos currículos, tornando a triagem um desafio para as ferramentas tradicionais, como bancos de dados SQL ou buscadores de texto. Isso ocorre pois as ferramentas tradicionais não possuem a capacidade de interpretar informações contextuais ou semânticas significativas. É aqui que entra o GPT-4 :D

- O objetivo principal é fornecer um dataset de curriculos para que o GPT-4 analise e responda com base nas informações, qual o melhor candidato para ocupar determinada posição, justificando a escolha. 

- Este modelo foi feito para fins de aprendizado, para melhorias futuras pode ser refatorado considerando a utilização da técnica de fine-tuning que consiste em treinar a rede neural pré-treinada do GPT-4, para uma tarefa específica com um conjunto menor de dados.

## Desenvolvimento <a name="development"></a>

[(Voltar ao topo)](#index)

- Para o desenvolvimento do trabalho, foi utilizada a linguagem Python e as bibliotecas Pandas (algoritmos e análise de dados) e OpenAI (processamento de linguagem natural GPT-4).

- O notebook contendo as anotações está disponível [AQUI](https://github.com/gomesfg/screening-resumes-using-generative-ai/blob/main/screening_resumes_using_generative_ai.ipynb).

- Para execução, o mesmo pode ser acessado pelo Google Colab clicando no botão abaixo:

  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gomesfg/screening-resumes-using-generative-ai/blob/main/screening_resumes_using_generative_ai.ipynb)

## Licença <a name="license"></a>

[(Voltar ao topo)](#index)

[The MIT License](https://opensource.org/licenses/MIT)
