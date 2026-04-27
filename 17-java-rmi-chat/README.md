# Java RMI Chat

Aplicação de chat distribuído com comunicação remota entre cliente e servidor via Java RMI.

## Objetivos

- Praticar arquitetura cliente-servidor com RMI
- Definir e implementar interfaces remotas
- Executar chamadas remotas entre processos Java

## Funcionalidades

- Iniciar servidor remoto com registro de serviço
- Conectar cliente ao servidor pelo registry RMI
- Trocar mensagens por métodos remotos

## Tecnologias Usadas

- Java
- Java RMI
- VS Code

## Como Executar

1. Baixe e extraia o arquivo `.zip` do repositório
2. Abra dois terminais na pasta `17-java-rmi-chat`
3. Compile os arquivos Java em um dos terminais:

```bash
javac *.java
```

4. Inicie o servidor:

```bash
java ChatServidor
```

5. No segundo terminal, inicie o cliente:

```bash
java ChatCliente
```

