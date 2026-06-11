<div align="center">

# 🆘 Local Disaster Relief & Volunteer Coordination System

**A relational database project for managing disaster relief operations and volunteer coordination**

![SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-Database-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

*A Database Systems course project at IIUC*

</div>

---

## 📖 About

This project models a database system for coordinating **local disaster relief efforts and volunteer management**. It is designed to help relief organizations track volunteers, disaster events, relief centers, donations, and resource distribution efficiently — ensuring help reaches affected areas in an organized manner.

The project was built using **Microsoft SQL Server (MSSQL)** and includes a complete relational schema, sample data, and a set of analytical queries demonstrating real-world use cases.

---

## 🗂️ What's Included

- 🧱 **Database Schema** — Fully normalized table structures with primary/foreign key relationships
- 🌱 **Sample Data** — Pre-populated records for testing and demonstration
- 🔍 **SQL Queries** — A collection of queries covering data retrieval, joins, aggregations, and reporting

---

## 🏗️ Database Design

The system is built around core entities commonly found in a disaster relief operation, including:

| Entity | Description |
|---|---|
| **Volunteers** | Stores volunteer details, contact info, and availability |
| **Disasters** | Records disaster events (type, location, severity, date) |
| **Relief Centers** | Locations where aid is collected and distributed |
| **Donations** | Tracks donations of money, food, and supplies |
| **Volunteer Assignments** | Maps volunteers to specific disasters/relief centers |
| **Resources / Supplies** | Inventory of items available for distribution |

> 💡 Relationships between these entities are enforced through primary and foreign keys, ensuring data integrity across the system.

---

## ⚙️ Tech Stack

| Technology | Purpose |
|---|---|
| **Microsoft SQL Server (MSSQL)** | Database management system |
| **T-SQL** | Schema definition, data manipulation, and queries |

---

## 🚀 Getting Started

### Prerequisites

- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) (or SQL Server Express)
- [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/ibrahim3761/Local-Disaster-Relief-and-Volunteer-Coordination.git
   cd Local-Disaster-Relief-and-Volunteer-Coordination
   ```

2. **Open SSMS** and connect to your local SQL Server instance.

3. **Run the schema script** to create the database and tables.

4. **Run the sample data script** to populate the tables with test records.

5. **Execute the query scripts** to explore reports and analytical results.

---

## 📊 Example Use Cases

- Find all volunteers assigned to a specific disaster relief operation
- View total donations received per relief center
- List available resources/supplies at each location
- Generate reports on volunteer participation across multiple disasters

---

## 🎓 Academic Context

> This project was developed as part of a **Database Systems** course in the B.Sc. in Computer Science & Engineering program at **International Islamic University Chittagong (IIUC)**.

It demonstrates core database concepts including:
- **Entity-Relationship (ER) Modeling**
- **Normalization** (reducing data redundancy)
- **Primary & Foreign Key Constraints**
- **Joins, Aggregations & Subqueries**
- **Data Integrity & Relational Design**

---

## 👨‍💻 Author

**Mohammad Ibrahim** — [@ibrahim3761](https://github.com/ibrahim3761) <br>
**Mostafa Ahnaf Hossain** — [@Ahnaf-221B](https://github.com/Ahnaf-221B)

---

<div align="center">
  <i>⭐ If you found this helpful, consider giving it a star!</i>
</div>