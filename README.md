# Employee Bank Branch Management (MS Access Database)

This repository contains a Microsoft Access database (`.accdb`) designed to manage employee banking information, including:

- Bank details
- Branch information
- Employee-bank relationship
- Capitalization using `UCase()` in queries

## 📂 File Included

- `f28b615d-08b5-419d-9532-7c13a91d10d8.accdb`: The main Access database file

## 🛠 Features

- MS Access Queries using `UCase()` to convert and format text fields
- Normalized table design
- Easy navigation and relationships between:
  - Bank
  - Branch
  - Employee

## 📝 Query Sample

```sql
SELECT UCase([Bank] & " " & [Branch]) AS BankBranchName
FROM YourTableName;
```

 Getting Started
Download or clone the repository

Open the .accdb file using Microsoft Access

Explore the tables, forms, and queries

📌 Notes
Requires MS Access 2016 or later.

Make sure macros are enabled if you use advanced functionality.
