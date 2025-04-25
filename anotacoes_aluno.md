# Anotações

## Fluxo da criação de um container

1. Criação de um diretório separado

2. No novo diretório, riação de um arquivo python 'app.py' que printa "Olá, Docker!"

3. No mesmo diretório, criar um arquivo sem extensão chamado 'Dockerfile' contendo:
    - FROM: seleciona a imagem python
    - COPY: copia arquivo python para container
    - CMD: setta a linha a ser executada no terminal

4. Construir um container usando 'docker build'

5. Executar o container usando 'docker run 'container_name' '

## Resumo
> Arquivo a ser executado --> Dockerfile --> Construir container --> Rodar container