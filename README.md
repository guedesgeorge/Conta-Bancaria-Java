🍵 Desafio Bancário em Java

Visão Geral

Este é um projeto simples em Java que simula funcionalidades básicas de um sistema bancário. O programa permite ao usuário realizar a consulta de saldo, transferência de valores, recebimento de valores e sair do sistema.

Funcionalidades

Consultar saldo: O usuário pode verificar o saldo atualizado da conta.

Transferir valor: Permite transferir um valor para outra conta, desde que o saldo seja suficiente.

Receber valor: Permite adicionar valores ao saldo da conta.

Sair: Finaliza o programa.

Tecnologias Utilizadas

Linguagem de programação: Java

Entrada de dados: Scanner

Estrutura do Código

1. Declaração de Variáveis

nome: Nome do cliente.

tipoConta: Tipo de conta bancária.

saldo: Saldo inicial da conta.

opcao: Opção selecionada pelo usuário no menu.

2. Interface de Usuário

O programa exibe as informações do cliente e apresenta um menu interativo:

String menu = """
    ** Digite sua opção **
    1 - Consultar saldo
    2 - Transferir valor
    3 - Receber valor
    4 - Sair

""";

3. Lógica de Negócio

O programa utiliza um laço while para manter o menu ativo até que o usuário selecione a opção de sair (4). Dependendo da escolha do usuário, o sistema executa uma das seguintes ações:

Opção 1: Exibe o saldo atualizado.

Opção 2: Solicita o valor a ser transferido e verifica se há saldo suficiente.

Opção 3: Solicita o valor a ser recebido e o adiciona ao saldo.

Opção inválida: Informa que a opção selecionada não é válida.

4. Saída de Dados

Mensagens dinâmicas informam ao usuário o status da conta e das operações realizadas.


Licença

Este projeto é de uso livre e pode ser modificado para fins educacionais ou pessoais.

Autor

Desenvolvido por [George Guedes].
