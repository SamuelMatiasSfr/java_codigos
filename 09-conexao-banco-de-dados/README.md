# Conexão com Banco de Dados

Projeto de conexão JDBC com MySQL para leitura de dados de uma base relacional.

## Objetivos

- Praticar conexão Java com MySQL usando JDBC
- Executar consultas SQL e percorrer resultados
- Organizar dados de banco em objetos Java

## Funcionalidades

- Abrir conexão com banco de dados
- Executar consultas em tabelas relacionadas
- Montar listas de entidades com os resultados obtidos

## Tecnologias usadas

- Java
- JDBC
- SQL
- MySQL
- VS Code

## Como executar

1. Baixe o repositório em formato zip
2. Extraia o zip em uma pasta local
3. Abra a pasta 09-conexao-banco-de-dados no terminal ou IDE
4. Configure o MySQL e importe o script LP2-10-bd-Gravadora.sql
5. Garanta que o arquivo mysql-connector-java-8.0.15.jar esteja no classpath
6. Compile o projeto:

```bash
javac -cp ".;mysql-connector-java-8.0.15.jar" ConexaoMaisSimples.java
```

7. Execute a aplicação:

```bash
java -cp ".;mysql-connector-java-8.0.15.jar" ConexaoMaisSimples
```

