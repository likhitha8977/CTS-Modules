# Entity Framework Core 8.0 Hands-On

## Overview

This hands-on module introduces Entity Framework Core 8.0 and demonstrates how to connect a .NET application with SQL Server using the Code First approach. The labs cover database creation, migrations, CRUD operations, and LINQ queries.

---

# Lab 1 – Understanding ORM

## Objective

To understand the concept of Object Relational Mapping (ORM) and the role of Entity Framework Core.

## Concepts Covered

- Object Relational Mapping (ORM)
- Entity Framework Core
- Entity Class
- Database Table Mapping

## Outcome

Learned how Entity Framework Core maps C# classes to SQL Server database tables and reduces the need for writing SQL queries manually.

---

# Lab 2 – Setting Up DbContext

## Objective

To configure DbContext for database communication.

## Concepts Covered

- DbContext
- DbSet
- SQL Server Connection
- appsettings.json Configuration

## Outcome

Successfully configured Entity Framework Core to communicate with SQL Server using DbContext.

---

# Lab 3 – Creating Migrations

## Objective

To generate the database using the Code First approach.

## Commands Used

```powershell
Add-Migration InitialCreate
Update-Database
```

## Concepts Covered

- Code First
- Migrations
- Database Generation

## Outcome

Successfully created the SQL Server database and tables using Entity Framework Core migrations.

---

# Lab 4 – Inserting Initial Data

## Objective

To insert records into the database.

## Concepts Covered

- Add()
- AddRange()
- SaveChanges()

## Outcome

Inserted sample product records into the SQL Server database successfully.

---

# Lab 5 – Querying Data

## Objective

To retrieve records from the database.

## Concepts Covered

- Find()
- FirstOrDefault()
- ToList()
- LINQ Queries

## Outcome

Successfully retrieved records using Entity Framework Core and LINQ.

---

# Lab 6 – Updating and Deleting Records

## Objective

To update and remove records from the database.

## Concepts Covered

- Update()
- Remove()
- SaveChanges()

## Outcome

Successfully modified and deleted records stored in SQL Server.

---

# Lab 7 – Writing LINQ Queries

## Objective

To perform advanced database operations using LINQ.

## Concepts Covered

- Where()
- OrderBy()
- Select()
- Count()
- FirstOrDefault()

## Outcome

Executed LINQ queries to filter, sort, and retrieve records efficiently.

---

# Software Used

- Visual Studio 2022
- .NET 8
- Entity Framework Core 8
- SQL Server 2022
- SQL Server Management Studio (SSMS)

---

# Key Concepts Learned

- ORM (Object Relational Mapping)
- Entity Framework Core
- Entity Class
- DbContext
- DbSet
- Code First Approach
- Migrations
- CRUD Operations
- LINQ Queries
- SQL Server Integration

---

# Conclusion

Through these labs, I learned how Entity Framework Core simplifies database operations in .NET applications. I understood how to create databases using the Code First approach, perform CRUD operations, execute LINQ queries, and manage SQL Server efficiently without writing extensive SQL code.