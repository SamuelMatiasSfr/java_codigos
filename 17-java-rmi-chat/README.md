# Java RMI Chat

Aplicação de chat distribuído com comunicação remota entre cliente e servidor via Java RMI.

## Objetivos

- Praticar arquitetura cliente-servidor com RMI
- Definir e implementar interfaces remotas
- Executar chamadas remotas entre processos Java

## Funcionalidades

- Inicia servidor remoto com registro de serviço
- Conecta cliente ao servidor pelo registry RMI
- Troca mensagens por métodos remotos

## Tecnologias usadas

- Java
- Java RMI

## Como executar

1. Baixe o repositório em formato zip
2. Extraia o zip em uma pasta local
3. Abra dois terminais na pasta 17-java-rmi-chat
4. Compile os arquivos Java em um dos terminais:

```bash
javac *.java
```

5. Inicie o servidor:

```bash
java ChatServidor
```

6. No segundo terminal, inicie o cliente:

```bash
java ChatCliente
```
