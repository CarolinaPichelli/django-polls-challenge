# Django Polls Challenge

## Sobre o projeto

O projeto consiste em uma aplicação simples de enquetes (*Polls*), onde é possível cadastrar perguntas e respostas, além de contabilizar votos para cada opção.

A partir da estrutura base do tutorial oficial, foram implementadas funcionalidades adicionais solicitadas no desafio, sem alterações nos templates ou nas views.

---

## Funcionalidades implementadas

- Cadastro de perguntas e respostas via Django Admin
- Registro de votos para cada resposta
- Método `total_votes`:
  - Retorna o total de votos de uma pergunta, somando os votos de todas as respostas associadas
- Método `has_votes`:
  - Retorna `True` caso a pergunta possua respostas com votos
  - Retorna `False` caso contrário
- Exibição automática dessas informações na tela de resultados (`/polls/results/`)

---

## Tecnologias utilizadas

- Python
- Django
- SQLite 

