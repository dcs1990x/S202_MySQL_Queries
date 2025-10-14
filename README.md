# Sprint 2, Task 2: MySQL Queries

This repository contains SQL query solutions for two database schemas: a retail store system and a university management system. The exercises focus on practicing syntax and the logic behind the relationships between tables of the schema.

## 📁 Project Structure

The project is organized into two main database schemas:

- **Store Database**
- **University Database**

## 💻 Technologies

- **MySQL 8.0+**
- **MySQL Workbench**

## 📋 Database Schemas

### 🏪 Store Database (`tienda`)

#### Tables Structure
- **`producto`** (codigo, nombre, precio, codigo_fabricante)
- **`fabricante`** (codigo, nombre)

#### Relationship
- `producto.codigo_fabricante` → `fabricante.codigo` (Foreign Key)

### 🎓 University Database (`universidad`)

#### Comprehensive academic schema including:
- Students (`alumno`)
- Professors (`profesor`)
- Departments (`departamento`)
- Degrees (`grado`)
- Courses (`asignatura`)
- Academic years (`curso_escolar`)
- Enrollments (`alumno_se_matricula_asignatura`)

## 📊 Query Categories

### Store Database Exercises

#### Basic Queries
- Simple SELECT statements with column manipulation
- String functions (UPPER, LOWER, substring operations)
- Mathematical operations (currency conversion, rounding)
- Sorting and ordering results

#### Intermediate Queries
- JOIN operations between products and manufacturers
- Filtering with WHERE conditions
- Using IN and NOT IN operators
- Pattern matching with LIKE operator

#### Advanced Queries
- Subqueries and correlated queries
- Aggregate functions without GROUP BY limitations
- Price comparisons and relative queries
- Handling NULL values and edge cases

### University Database Exercises

#### Student Data Management
- Student information retrieval
- Birth date filtering
- Contact information validation
- Enrollment history

#### Professor & Department Relations
- Department-professor associations
- Course assignment tracking
- Contact information validation

#### Academic Structure
- Course scheduling by semester and year
- Degree program analysis
- Credit calculations per course type
- Academic year statistics

#### Complex JOIN Operations
- LEFT JOIN and RIGHT JOIN implementations
- Handling missing associations
- Department with no professors
- Courses without assigned professors

#### Aggregate Analysis
- Student population statistics
- Professor count per department
- Course count per degree program
- Enrollment statistics by academic year
- Course assignments per professor

## ✅ SQL Syntax Practiced

- **Basic Operations**: SELECT, WHERE, ORDER BY, LIMIT
- **String Functions**: CONCAT, UPPER, LOWER, SUBSTRING
- **Mathematical Functions**: ROUND, TRUNCATE, currency conversion
- **JOIN Operations**: INNER JOIN, LEFT JOIN, RIGHT JOIN
- **Aggregate Functions**: COUNT, SUM, AVG with GROUP BY
- **Subqueries**: Correlated and non-correlated subqueries
- **Pattern Matching**: LIKE operator with wildcards
- **Data Filtering**: IN, NOT IN, EXISTS operators
- **Null Handling**: IS NULL, IS NOT NULL conditions

## 🚀 How to Use

1. **Clone the repository**
2. **Import the database schemas**:
   ```sql
   -- For Store database
   SOURCE schema_tienda.sql;
   
   -- For University database
   SOURCE schema_universidad.sql;

## 👨‍💻 Author   
Developed by Daniel Caldito Serrano as part of the Java Back-end Development Bootcamp at the IT Academy.
