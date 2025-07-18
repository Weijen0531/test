# SQL Structure Query Language 
- 官方網站 https://neon.com/postgresql/tutorial
## Managing Tables
-- CREATE TABLE
> CREATE TABLE [IF NOT EXISTS] table_name (
   column1 datatype(length) column_constraint,
   column2 datatype(length) column_constraint,
   ...
   table_constraints
);
> 

# DDL(定義資料語言)
**建立、修改、刪除資料庫和資料表的SQL指令類別**

在SQL中，針對資料庫與資料表的「建立（Create）」、「修改（Alter）」、「刪除（Drop）」等操作，這些指令都屬於**資料定義語言（DDL, Data Definition Language）**的範疇。

### DDL（資料定義語言）簡介

DDL主要用於**定義與管理資料庫結構**，包括：

- **CREATE**：建立新的資料庫或資料表
- **ALTER**：修改現有的資料表結構
- **DROP**：刪除資料庫或資料表
- **TRUNCATE**：清空資料表內容但保留結構

- ### 常見DDL指令範例

| 操作   | 指令範例                  | 說明                   |
|--------|---------------------------|------------------------|
| 建立   | CREATE DATABASE / TABLE   | 建立資料庫或資料表     |
| 修改   | ALTER TABLE               | 修改資料表結構         |
| 刪除   | DROP DATABASE / TABLE     | 刪除資料庫或資料表     |
