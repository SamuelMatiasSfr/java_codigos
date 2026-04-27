# Java RMI Cadastro de Pessoas

Sistema distribuído para cadastro de pessoas com operações remotas e dados persistidos em CSV.

## Objetivos

- Praticar RMI com operações de cadastro
- Organizar entidades e serviços remotos
- Integrar interface gráfica com backend remoto

## Funcionalidades

- Iniciar servidor remoto com operações de cadastro e consulta
- Carregar e manipular dados de pessoas no arquivo pessoal.csv
- Permitir interação via cliente e janela gráfica

## Tecnologias Usadas

- Java
- Java RMI
- Java Swing
- VS Code

## Como Executar

1. Baixe e extraia o arquivo `.zip` do repositório
2. Abra dois terminais na pasta `18-java-rmi-cadastro-pessoas`
3. Compile os arquivos Java:

```bash
javac *.java
```

4. Inicie o servidor:

```bash
java ServidorInterfacePessoaImplementada
```

5. No segundo terminal, execute o cliente gráfico:

```bash
java Cliente
```

ou

```bash
java Janela
```

