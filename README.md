📚 Sistema de Biblioteca Inteligente

Jaqueline da Silva Gomes <br>
Curso: Análise e Desenvolvimento de Sistemas <br>
Universidade Cruzeiro do Sul
Meu Repositório: https://github.com/jaqueline-silvajf/Atividade-04-Novembro.git
----
📌 Sobre o Projeto

O Sistema de Biblioteca Inteligente é um modelo de banco de dados relacional projetado para gerenciar livros, usuários, funcionários, empréstimos, multas e reservas de uma biblioteca.

O objetivo do projeto é oferecer uma estrutura robusta e bem organizada para apoiar sistemas de controle de acervo e circulação, assegurando integridade dos dados, relacionamentos consistentes e padronização das informações.

Este repositório contém o script SQL completo para criação das tabelas, relacionamentos e regras de integridade no MySQL.
----
🗂️ Estrutura do Banco de Dados

O banco de dados é composto pelas seguintes entidades principais:

1 → Livros

Registra todas as informações do acervo.
Campos principais: título, autor, ano de publicação, gênero, editora, status.

2 → Usuários
Armazena dados dos leitores cadastrados.

3 → Funcionários
Contém informações sobre os colaboradores responsáveis pelo atendimento.

4 → Empréstimos
Tabela que relaciona livros, usuários e funcionários no processo de empréstimo.

5 → Multas
Controla multas aplicadas por atraso na devolução.

6 → Reservas
Registra solicitações de reserva feitas pelos usuários.
---
🔗 Relacionamentos
Empréstimos se relacionam com:

Livros,
Usuários,
Funcionários,
Multas,
Empréstimos,
Reservas,
Livros,
Usuários

Todos os relacionamentos foram implementados com chaves estrangeiras e regras de integridade referencial, garantindo consistência e evitando dados órfãos.
---
🛠️ Tecnologias Utilizadas

MySQL 5.7+ ou MariaDB

Clientes SQL: MySQL Workbench, DBeaver ou terminal MySQL
---
▶️ Como Executar o Projeto

Instale o MySQL em sua máquina.

Abra o MySQL Workbench (ou outro cliente de sua preferência).

Copie o arquivo SQL disponível neste repositório.

Execute o script para criar o banco de dados:
CREATE DATABASE biblioteca;
USE biblioteca;

-- (demais comandos de criação das tabelas)
---
BANCO DE DADOS biblioteca:


![BANCO DE DADOS biblioteca](https://github.com/user-attachments/assets/b832760e-3c9e-40b5-babc-9aa15ff56377)

---
📘 Objetivo Acadêmico

Este projeto foi desenvolvido como atividade prática da disciplina Modelagem e Desenvolvimento de Banco de Dados, visando proporcionar experiência na criação de bancos relacionais completos, com tabelas bem estruturadas e regras de negócio implementadas.
---
🧑‍💻 Autora

Jaqueline da Silva Gomes <br>
Curso: Análise e Desenvolvimento de Sistemas <br>
Universidade Cruzeiro do Sul

