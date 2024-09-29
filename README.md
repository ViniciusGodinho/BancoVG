# BancoVG
desafio banco pyton

# Simulação de Banco em Python

Este projeto é uma simulação simples de um banco em Python, onde você pode realizar operações como depósitos, saques e visualizar o extrato de uma conta bancária. 

## Funcionalidades

O programa implementa as seguintes funcionalidades:

1. **Depósito**:
   - Permite realizar depósitos em sua conta.
   - O valor do depósito deve ser positivo, caso contrário a operação não será permitida.
   - O depósito é registrado no extrato.

2. **Saque**:
   - Permite realizar saques com as seguintes restrições:
     - Limite de 3 saques por dia.
     - O valor máximo de saque por operação é de R$500.
     - Não é permitido sacar mais do que o saldo disponível.
   - Cada saque realizado é registrado no extrato.

3. **Extrato**:
   - Exibe todas as movimentações realizadas na conta (depósitos e saques).
   - Exibe o saldo atual da conta.

4. **Limite Diário de Saques**:
   - Há um limite de 3 saques diários.
   - O método `resetar_saques_diarios` pode ser usado para simular o reset diário do limite de saques.

## Como Usar

1. Clone este repositório para o seu ambiente local:
   ```bash
   git clone https://github.com/seu-usuario/simulacao-banco.git
