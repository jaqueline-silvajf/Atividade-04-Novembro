📚 Sistema de Biblioteca Inteligente
Autora: Jaqueline da Silva Gomes
Curso: Análise e Desenvolvimento de Sistemas – Cruzeiro do Sul
📌 Sobre o Projeto

O Sistema de Biblioteca Inteligente é um modelo de banco de dados desenvolvido para gerenciar livros, usuários, funcionários, empréstimos, multas e reservas dentro de uma biblioteca.

O objetivo é fornecer uma estrutura robusta e organizada para apoiar o desenvolvimento de sistemas de controle de acervo e circulação, garantindo integridade dos dados e regras de relacionamento bem definidas.

Este repositório contém o script SQL completo para criação das tabelas e relações no MySQL.

🗂️ Estrutura do Banco de Dados

O banco é composto pelas seguintes tabelas principais:

1. Livros

Registra informações sobre o acervo da biblioteca.
Campos principais: título, autor, ano de publicação, gênero, editora e status.

2. Usuários

Armazena os dados dos leitores cadastrados na biblioteca.

3. Funcionários

Guarda informações sobre funcionários responsáveis pelos atendimentos.

4. Empréstimos

Relação entre livros, usuários e funcionários durante um empréstimo.

5. Multas

Controla multas associadas a atrasos na devolução.

6. Reservas

Registra solicitações de reserva de livros pelos usuários.

🔗 Relacionamentos

Emprestimos se relacionam com:

Livros

Usuários

Funcionários

Multas dependem de Emprestimos

Reservas se relacionam com:

Livros

Usuários

Todos os relacionamentos foram criados com chaves estrangeiras e regras de integridade referencial.

🛠️ Tecnologias Utilizadas

MySQL 5.7+ ou MariaDB

Workbench, DBeaver ou terminal MySQL para execução do script

▶️ Como Executar o Projeto

Instale o MySQL na sua máquina.

Abra o MySQL Workbench ou seu cliente preferido.

Copie o arquivo SQL disponível neste repositório.

Execute o script completo para criar o banco:

CREATE DATABASE biblioteca;
USE biblioteca;

-- (demais comandos de criação das tabelas)
![print](https://github.com/user-attachments/assets/4941d6c0-7475-4596-8ac5-f8fd3409236a)

📘 Objetivo Acadêmico

Este projeto foi desenvolvido como atividade prática na disciplina de Modelagem e Desenvolvimento de Banco de Dados, proporcionando experiência na construção de modelos relacionais completos e funcionais.

🧑‍💻 Autora

Jaqueline da Silva Gomes
Curso de Análise e Desenvolvimento de Sistemas
Universidade Cruzeiro do Sul

