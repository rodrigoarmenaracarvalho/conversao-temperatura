# Projeto conversão de temperatura

### Sobre o projeto
Desafio 1 da Jornada DevOps de Elite. O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.
Após realizar o clone do repositório, realizar o build e o run da imagem:
    1) docker build -t rodrigocarvm/conversao-temperatura:v1 .
    2) docker run -d --name app-conversao-temp -p 8080:8080 rodrigocarvm/conversao-temperatura:v1

### Observações do projeto
A aplicação é exposta usando a porta 8080
