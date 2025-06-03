# Sistema Bancário em Python — Orientado a Objetos com Transferência e Persistência

Este projeto é uma versão aprimorada de um **sistema bancário em Python**, desenvolvido com **programação orientada a objetos**. Ele permite ao usuário interagir com o sistema via terminal para realizar **operações bancárias completas**, como depósitos, saques, transferências entre contas, consulta de saldo e visualização de extrato. Os dados são salvos em **arquivos JSON**, garantindo persistência mesmo após o encerramento do programa.

## Funcionalidades

-  **Consulta de saldo**: Exibe o saldo atual da conta.
-  **Depósito**: Adiciona um valor ao saldo da conta e registra a operação.
-  **Saque**: Retira um valor da conta, se houver saldo suficiente.
-  **Extrato bancário**: Mostra todas as transações com data e hora.
-  **Transferência entre contas**: Permite enviar valores de uma conta para outra.
-  **Persistência de dados**: Salva automaticamente o saldo e o extrato em arquivos `.json`.
-  **Validação de entradas**: Garante que valores digitados sejam válidos.

##  Estrutura Orientada a Objetos

- Classe `ContaBancaria`: representa uma conta com saldo, número e extrato.
- Métodos:
  - `consultar_saldo()`
  - `depositar(valor)`
  - `sacar(valor)`
  - `exibir_extrato()`
  - `transferir(conta_destino, valor)`
- Funções auxiliares:
  - `salvar_dados(conta, filename)`
  - `carregar_dados(filename)`

##  Tecnologias Usadas

- **Python 3.x**
- Módulos padrão:
  - `datetime` — registro de data e hora
  - `json` — leitura e gravação de dados
  - `os` — verificação de existência de arquivos

##  Como Usar

1. Clone este repositório para sua máquina local:

   ```bash
   git clone https://github.com/maniglia-vithor/proj05_sistema_bancario_poo.git
