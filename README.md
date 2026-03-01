<h1 align="center"> 🎢 Database — Parque de Diversões </h1>

<p align="center">
  <img src="assets\media\banner\banner.png" alt="Banner" width="600">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MySQL-5.7+-green">
  <img src="https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/status-complete-brightgreen">
  <img src="https://img.shields.io/badge/project-academic-informational">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg">
  </a>
</p>

This project consists of the development of a **relational database** for managing an **amusement park**.  
The main goal is to organise and relate information about attractions, maintenance records, employees, visitors and tickets, ensuring **data integrity**, **consistency** and **good database design practices**.

The database was developed using **MySQL** and serves as both an **academic project** and a **portfolio piece**, demonstrating fundamental knowledge of **relational databases**.

---

## 📂 Project Structure

```

parque-diversoes-db/
│
├── database/                              → Database layer
│   └── sql/                               → SQL scripts organized by responsibility
│       ├── schema/                        → Database structural definition
│       │   ├── create_database.sql        → Database creation and schema selection
│       │   ├── indexes.sql                → Indexes for query performance optimization
│       │   └── tables.sql                 → Table creation, relationships, and constraints
│       │
│       └── views/                         → SQL views for complex queries and reporting
│           └── view.sql                   → Database view definitions
│
├── docs/                                  → Project documentation
│   └── images/                            → Visual assets used in the README and documentation
│       ├── banner/                        → Project banners
│       ├── db/                            → Database-related images
│       └── diagrams/                      → ER and relational diagrams
│
├── .gitignore                             
├── LICENSE                               
└── README.md                              


````

---

## 🗄️ Database Structure

The database is composed of **6 main tables**, organised using a normalised structure:

- **Atracao** — Information about the park attractions  
- **Manutencao** — Maintenance records for attractions  
- **Funcionario** — Employees responsible for maintenance  
- **Manutencao_Funcionario** — Associative table (N:M relationship)  
- **Visitante** — Park visitors  
- **Bilhete** — Tickets purchased for attractions  

Includes:

- **1:N** and **N:M** relationships  
- Primary and foreign keys  
- Constraints (`CHECK`, `NOT NULL`, `DEFAULT`)  
- Indexes to optimise query performance  

---

## 🎯 Project Objectives

This project was created with the purpose of:

- Applying **database modelling concepts**
- Working with **1:N** and **N:M** relationships
- Ensuring **referential integrity**
- Applying **SQL best practices**
- Creating a **realistic and functional** database
- Consolidating knowledge acquired in the **GPSI course**

---

## 📌 Note

This project was developed for **academic and educational purposes**, as part of the learning process in relational databases.

---

## 👤 Author

Project developed within the professional course  
**Management and Programming of Information Systems (GPSI)**  

* **School:** Escola Profissional Bento Jesus Caraça (EPBJC)  
* **Subject:** PSI  
* **Author:** Andérson Brito  

---

## 📄 License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for more details.
