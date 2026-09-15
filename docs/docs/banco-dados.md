# Banco de Dados

## Tabela: Usuários

- id_usuario
- nome
- email
- senha
- tipo_usuario

## Tabela: Livros

- id_livro
- titulo
- autor
- isbn
- editora
- ano_publicacao
- status

## Tabela: Empréstimos

- id_emprestimo
- id_usuario
- id_livro
- data_emprestimo
- data_devolucao
- status

## Relacionamentos

Um usuário pode realizar vários empréstimos.

Um livro pode participar de vários empréstimos ao longo do tempo.

Cada empréstimo está relacionado a um usuário e a um livro.
