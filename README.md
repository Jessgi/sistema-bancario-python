# Otimização de Sistema Bancário em Python

Este projeto é uma solução para o desafio de projeto "Otimizando o Sistema Bancário com Funções Python" da Digital Innovation One (DIO).

## Descrição

O objetivo foi refatorar um sistema bancário simples, que inicialmente operava com um único arquivo, para uma versão mais modular e funcional. As operações de depósito, saque e extrato foram separadas em funções, e novas funcionalidades para criar usuários e contas bancárias foram adicionadas.

## Funcionalidades

- **Depositar:** Adiciona valores à conta, apenas valores positivos são permitidos.
- **Sacar:** Permite retirar valores da conta, sujeito a um limite por saque e um número máximo de saques diários.
- **Extrato:** Exibe todas as transações realizadas e o saldo atual da conta.
- **Novo Usuário:** Cadastra um novo cliente com nome, data de nascimento, CPF e endereço. O sistema não permite CPFs duplicados.
- **Nova Conta:** Cria uma nova conta corrente vinculada a um usuário existente. O número da agência é fixo e o número da conta é sequencial.
- **Listar Contas:** Exibe todas as contas cadastradas.

## Tecnologias Utilizadas

- **Python 3**

## Como Executar

1. Clone o repositório (ou baixe os arquivos).
2. Navegue até a pasta do projeto.
3. Execute o script principal no seu terminal:
   ```bash
   python nome_do_seu_arquivo.py
