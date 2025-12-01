# CARTON - Locadora de Veículos

## Sistema de Locadora de Veículos - Projeto SQL

Este projeto implementa um banco de dados relacional completo para uma **locadora de veículos**, incluindo criação de tabelas, povoamento com dados fictícios e consultas SQL usando comandos DML (`SELECT`, `INSERT`, `UPDATE`, `DELETE`).  
O desenvolvimento segue as instruções da disciplina de **Modelagem de Banco de Dados**.

## Objetivos da Atividade

- Criar tabelas respeitando chaves primárias e estrangeiras.  
- Inserir registros utilizando comandos `INSERT`.  
- Realizar consultas SQL com `SELECT`, `WHERE`, `ORDER BY`, `JOIN`, etc.  
- Manipular dados com `UPDATE` e `DELETE`.  
- Versionar o projeto em um repositório público no GitHub.  

## Estrutura do Banco de Dados

O banco de dados contém as seguintes tabelas:

- **CategoriaVeiculo:** Categorias dos veículos (SUV, Sedan, Hatch).  
- **Veiculo:** Marca, placa, quilometragem e categoria.  
- **Cliente:** Dados pessoais dos clientes.  
- **Reserva:** Reservas realizadas por clientes.  
- **Locacao:** Locações associadas às reservas e veículos.  
- **Devolucao:** Registro final da devolução e valores.

Todos os relacionamentos foram implementados corretamente utilizando `FOREIGN KEY`.

## Como Executar

1. Instale o **SQLiteStudio** (ou qualquer outro cliente SQLite).  
2. Crie um novo banco de dados vazio.  
3. Abra e execute o arquivo deste repositório.

## Conclusão

O projeto implementa com sucesso um modelo lógico completo de um sistema de locadora de veículos, incluindo criação, normalização, povoamento do banco e consultas SQL variadas.
