<h1 align="center"> 🎢 Base de Dados — Parque de Diversões </h1>

<p align="center">
  <img src="assets/imagens/banner-parque_diversoes.png" alt="Banner" width="600">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/mysql-5.7+-green">
  <img src="https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/status-completo-brightgreen">
  <img src="https://img.shields.io/badge/project-academic-informational">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg">
  </a>
</p>


Este projeto consiste no desenvolvimento de uma **base de dados relacional** para a gestão de um **parque de diversões**. O objetivo principal é organizar e relacionar informação sobre atrações, manutenções, funcionários, visitantes e bilhetes, garantindo **integridade dos dados**, **coerência** e **boas práticas de modelação**.

A base de dados foi desenvolvida em **MySQL** e serve como projeto académico e de portfólio, demonstrando conhecimentos fundamentais em **bases de dados relacionais**.

---

## 📂 Estrutura do Projeto

```
parque-diversoes-db/
│
├── src/
|   └── diagramas/                    → Diagramas da base de dados (ER / Relacional)
|   └── imagens/                      → Imagens utilizadas no projeto         
|
├── src/
│   └── parque_de_diversoes.sql       → Script de criação da base de dados
└── README.md
```

---

## 🗄️ Estrutura da Base de Dados

A base de dados é composta por **6 tabelas principais**, organizadas de forma normalizada:

* **Atracao** — Informação sobre as atrações do parque
* **Manutencao** — Registos de manutenção das atrações
* **Funcionario** — Funcionários responsáveis pelas manutenções
* **Manutencao_Funcionario** — Tabela associativa (relação N:M)
* **Visitante** — Visitantes do parque
* **Bilhete** — Bilhetes adquiridos para as atrações

Inclui:

* Relacionamentos **1:N** e **N:M**
* Chaves primárias e estrangeiras
* Restrições (`CHECK`, `NOT NULL`, `DEFAULT`)
* Índices para otimização de consultas

---

## 🎯 Objetivos do Projeto

Este projeto foi criado com o objetivo de:

* Aplicar conceitos de **modelação de bases de dados**
* Trabalhar com relacionamentos **1:N** e **N:M**
* Garantir **integridade referencial**
* Utilizar boas práticas de SQL
* Criar uma base de dados **realista e funcional**
* Consolidar conhecimentos adquiridos no curso de **GPSI**

---

## ▶️ Como executar o projeto

1. Abrir o MySQL (MySQL Workbench ou outro cliente)
2. Executar o ficheiro:

   ```sql
   src/parque_de_diversoes.sql
   ```
3. A base de dados será criada automaticamente

---

## 📌 Nota

Este projeto foi desenvolvido com fins **académicos e educativos**, sendo parte do processo de aprendizagem em bases de dados relacionais.

---

## 👤 Autor

Projeto desenvolvido no âmbito do curso profissional de  
**Gestão e Programação de Sistemas Informáticos (GPSI)**

**Escola:** Escola Profissional Bento Jesus Caraça (EPBJC)  
**Disciplina:** PSI  
**Autor:** Andérson Brito

---

## Licença
Este projeto está licenciado sob a Licença MIT. Veja o ficheiro [LICENSE](LICENSE) para mais detalhes.

