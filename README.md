# 💰 Desafio Bancário em Java

## 📌 Visão Geral

Este é um projeto simples em Java que simula funcionalidades básicas de um sistema bancário. O objetivo é praticar conceitos fundamentais como variáveis, estruturas de controle, entrada e saída de dados, e lógica de programação.

## 🧩 Funcionalidades

- **Consultar saldo:** O usuário pode verificar o saldo atualizado da conta.
- **Transferir valor:** Permite transferir um valor para outra conta, desde que o saldo seja suficiente.
- **Receber valor:** Permite adicionar valores ao saldo da conta.
- **Sair:** Finaliza o programa.

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Java
- **Entrada de dados:** Scanner

## 🧱 Estrutura do Código

### 🔸 Declaração de Variáveis

- `nome`: Nome do cliente.
- `tipoConta`: Tipo de conta bancária.
- `saldo`: Saldo inicial da conta.
- `opcao`: Opção selecionada pelo usuário no menu.

### 🔸 Interface de Usuário

Exibe as informações do cliente e apresenta um menu interativo:

```java
String menu = """
** Digite sua opção **
1 - Consultar saldo
2 - Transferir valor
3 - Receber valor
4 - Sair
""";
