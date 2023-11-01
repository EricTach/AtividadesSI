# Docker Compose for Kafka

Este repositório fornece um Docker Compose que permite configurar um ambiente Kafka local, utilizando um producer e um consumer

## Configuração

-Docker precisa ser instaldo no sistema <br>
-Python precisa ser instalado no sistema <br>
-Utilize "pip install kafka-python" no terminal <br>

## Como Usar

1. Clone este repositório:
   
2. Execute o Docker Compose -> Utilizando "docker-compose up"

3. Execute o produtor de exemplo para enviar mensagens -> utilizando python producer.py <br>
Como deve ficar o resultado: <br> ![image](https://github.com/EricTach/AtividadesSI/assets/99208930/47543b47-d6a1-403a-99cf-b7e585f90fc1)

O código enviará 100 mensagens, contando até 100, pelo tópico especificado

4. O consumidor exibirá as mensagens recebidas, ao executar o comando python consumer.py. <br>
Resultado: <br> ![image](https://github.com/EricTach/AtividadesSI/assets/99208930/e93042c5-7a02-45a4-ab63-99d95e21c6fa)

## Fonte de inspiração
Link: https://towardsdatascience.com/kafka-docker-python-408baf0e1088




