# Java RMI Cadastro de Pessoas

Sistema distribuído para cadastro de pessoas com operações remotas e dados persistidos em CSV.

## Objetivos

- Praticar RMI com operações de cadastro
- Organizar entidades e serviços remotos
- Integrar interface gráfica com backend remoto

## Funcionalidades

- Inicia servidor remoto com operações de cadastro e consulta
- Carrega e manipula dados de pessoas no arquivo pessoal.csv
- Permite interação via cliente e janela gráfica

## Tecnologias usadas

- Java
- Java RMI
- Java Swing
- CSV

## Como executar

1. Baixe o repositório em formato zip
2. Extraia o zip em uma pasta local
3. Abra dois terminais na pasta 18-java-rmi-cadastro-pessoas
4. Compile os arquivos Java:

```bash
javac *.java
```

5. Inicie o servidor:

```bash
java ServidorInterfacePessoaImplementada
```

6. No segundo terminal, execute o cliente gráfico:

```bash
java Cliente
```

ou

```bash
java Janela
```
