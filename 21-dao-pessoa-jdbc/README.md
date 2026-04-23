# DAO Pessoa com JDBC

Projeto de acesso a dados com padrão DAO para operações de pessoa em banco MySQL.

## Objetivos

- Aplicar padrão DAO para separar persistência da regra de negócio
- Praticar integração Java com MySQL via JDBC
- Organizar CRUD com interface e implementação específica

## Funcionalidades

- Definir contrato DAO para entidade Pessoa
- Implementar acesso a banco com JDBC
- Listar e manipular registros de pessoas pelo programa principal

## Tecnologias usadas

- Java
- JDBC
- SQL
- MySQL
- Padrão de Projeto DAO

## Como executar

1. Baixe o repositório em formato zip
2. Extraia o zip em uma pasta local
3. Abra a pasta 21-dao-pessoa-jdbc no terminal ou IDE
4. Garanta que o arquivo mysql-connector-java-8.0.15.jar esteja dentro da pasta do projeto
5. Configure o banco MySQL com a estrutura esperada pelo código, usando o script do arquivo script_banco.txt
6. Compile conforme orientação do projeto:

```bash
javac -cp ".;mysql-connector-java-8.0.15.jar" Main.java
```

7. Execute conforme orientação do projeto:

```bash
java -cp ".;mysql-connector-java-8.0.15.jar" Main
```

