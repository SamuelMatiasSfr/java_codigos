# Java RMI Jogo da Forca

Jogo da forca distribuído com servidor RMI responsável pela lógica e cliente para interação.

## Objetivos

- Praticar comunicação distribuída com Java RMI
- Implementar lógica de jogo em arquitetura cliente-servidor
- Trabalhar leitura de palavras em arquivo 

## Funcionalidades

- Selecionar palavra e controlar tentativas no servidor RMI
- Enviar letras e receber retorno do estado do jogo no cliente
- Usar arquivo palavras.txt como base de palavras

## Tecnologias usadas

- Java
- Java RMI
- VS Code

## Como executar

1. Baixe o repositório em formato zip
2. Extraia o zip em uma pasta local
3. Abra dois terminais na pasta 26-java-rmi-jogo-da-forca
4. Compile os arquivos Java:

```bash
javac *.java
```

5. Inicie o servidor:

```bash
java Servidor
```

6. No segundo terminal, execute o cliente:

```bash
java ClienteForca
```

