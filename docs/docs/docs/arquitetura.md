# Arquitetura do Sistema

## Visão Geral

O Sistema de Biblioteca será organizado em três camadas principais:

1. Interface do Usuário
2. Lógica de Negócio
3. Banco de Dados

## Interface do Usuário

É a parte visual do sistema, onde os usuários poderão realizar as operações.

Exemplos:

- Tela de Login
- Tela Inicial
- Cadastro de Livros
- Cadastro de Usuários
- Empréstimos
- Devoluções

## Lógica de Negócio

Responsável por aplicar as regras do sistema.

Exemplos:

- Verificar se o livro está disponível.
- Verificar se o usuário possui empréstimos atrasados.
- Registrar empréstimos.
- Registrar devoluções.

## Banco de Dados

Responsável por armazenar as informações de:

- Usuários
- Livros
- Empréstimos

## Fluxo do Sistema

Usuário → Interface → Lógica de Negócio → Banco de Dados
