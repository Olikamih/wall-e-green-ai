# Wall-E Green AI

Chatbot baseado no personagem WALL-E focado em sustentabilidade e tecnologia ambiental.

## Tecnologias

- Python
- Hugging Face Transformers
- Gradio

## Arquitetura do Sistema

O sistema funciona da seguinte forma:

1. O usuário envia uma pergunta pela interface web.
2. A interface foi criada utilizando Gradio.
3. A pergunta é enviada para o modelo "?".
4. O modelo gera uma resposta baseada no dataset treinado.
5. A resposta é exibida na interface para o usuário.

# Exemplos de perguntas ao chatbot

Pergunta:
Como podemos reduzir o consumo de energia no planeta?

Resposta esperada:
Podemos utilizar fontes renováveis como energia solar e eólica.

---

Pergunta:
O que é reflorestamento?

Resposta esperada:
Reflorestamento é o processo de plantar árvores em áreas desmatadas para restaurar o ecossistema.

## Como executar o projeto

1. Clone o repositório

git clone https://github.com/seuusuario/wall-e-green-ai

2. Instale as dependências

pip install -r requirements.txt

3. Execute o chatbot

python app/chatbot_interface.py

## Objetivo do projeto

Este projeto tem como objetivo criar um chatbot educacional inspirado no personagem Wall-E
capaz de responder perguntas relacionadas a:

- sustentabilidade
- reflorestamento
- consumo energético
- preservação ambiental