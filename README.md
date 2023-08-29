# Desafio DIO Santander Bootcamp (ETL com Python)

## Contexto
Você é um cientista de dados no Santander e recebeu a tarefa de somar os pontos conquistados pelos clientes. Seu objetivo é usar o Python para ler três arquivos CSV, identificar as transações de cada cliente e somar os pontos obtidos. Depois você deve usar poder da IA Generativa para criar mensagens personalizadas que serão entregues a cada cliente. Se o cliente possuir mais de 100 pontos deve ser uma mensagem de parabéns, se estiver entre 80 e 99, deve ser uma mensagem de "quase lá", se estiver entre 20 e 79, a mensagem deve ser de incetivo, mas se estiver abaixo de 20 a mensagem deve demonstrar as qualidades do banco e convidar o cliente para utilizar mais serviços. Cada mensagem vai ser entregue por e-mail para o cliente.

## Condições do problema
1. Você recebeu os arquivos: **users.csv**, **transactions.csv** e **transaction_types.csv**. 
2. O trabalho começa lendo os dados e relacionando as informações.
3. Na sequencia apuramos os pontos que cada cliente conquistou e armazenamos dentro de uma nova coluna.
4. Consumimos a API do chatGPT e armazemanos as mensagems dentro do dataframe.
5. Por fim lemos o nosso dataframe final e enviamos os e-mails personalizados.

## **E**xtract
Ler e extrair os dados dos arquivos e carregar dentro dos dataframes.

## **T**ransform
Utilize a API do OpenAI GPT-3.5 para gerar uma mensagem de marketing personalizada para cada usuário e prepare para envio por e-mail.

## **L**oad
Percorre a lista de usuários e envia a mensagem de marketing gerada pelo ChatGPT.