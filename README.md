# techchallenge_f3
Tech Challenge - Fase 03


# Projeto de Fine Tuning referente ao Tech Challenge da fase 03 da Pós em IA para Devs da FIAP

# Grupo 50
Integrantes:
Leandro Juvenal Marques
leandrojuvenal@correios.com.br

Ana Paula de Sa Lopes de Simone
analopes@correios.com.br

Christiane Pinheiro Campelo da Silva
christiane@correios.com.br

# Passos:

Download do arquivo de informações de produtos da Amazon (em torno de 2 milhões e 300 mil registros)

Dividimos o arquivo em 23 partes de até 100.000 registros

Pré-preparo das informações: exclusão de linhas em branco e registros/colunas inválidos; mantivemos apenas as colunas "title" e "content"

Utilizamos os Chat GPT para gerar o resumo da coluna "content", que serviu como output no treino a ser realizado no modelo

Treinamos o modelo usando o Llama ("unsloth/llama-3-8b-Instruct-bnb-4bit") e realizamos o Fine Tuning 

Os testes realizados tanto com dados da base de treino e dados externos se mostraram favoráveis.
