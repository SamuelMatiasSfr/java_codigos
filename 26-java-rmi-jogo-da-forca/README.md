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

## Tecnologias Usadas

- Java
- Java RMI
- VS Code

## Como Executar

1. Baixe e extraia o arquivo `.zip` do repositório
2. Abra dois terminais na pasta `26-java-rmi-jogo-da-forca`
3. Compile os arquivos Java:

```bash
javac *.java
```

4. Inicie o servidor:

```bash
java Servidor
```

5. No segundo terminal, execute o cliente:

```bash
java ClienteForca
```

