# Gestão de Notas de Alunos com Padrões de Projeto

Sistema de notas de alunos com DAO, Proxy e Singleton integrado a banco MySQL.

## Objetivos

- Aplicar múltiplos padrões de projeto em um mesmo sistema
- Praticar persistência com JDBC e SQL

## Funcionalidades

- Cadastrar e consultar notas de alunos no banco
- Calcular médias e permitir atualizar notas
- Usar DAO para acesso a dados, Proxy para controle e Singleton para instância única

## Tecnologias usadas

- Java
- JDBC
- SQL
- MySQL
- Padrões de Projeto: DAO, Proxy e Singleton

## Como executar

1. Baixe o repositório em formato zip
2. Extraia o zip em uma pasta local
3. Abra a pasta 27-gestao-notas-alunos-padroes-projeto no terminal ou IDE
4. Garanta que o arquivo mysql-connector-java-8.0.15.jar esteja dentro da pasta do projeto
5. Configure o MySQL e importe o arquivo notas.sql
6. Compile conforme orientação do projeto:

```bash
javac -cp ".;mysql-connector-java-8.0.15.jar" Main.java
```

7. Execute conforme orientação do projeto:

```bash
java -cp ".;mysql-connector-java-8.0.15.jar" Main
```

