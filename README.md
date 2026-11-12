# SQL Police Department · Query Exercises

Colección de consultas SQL escritas para resolver ejercicios de análisis sobre una base de datos ficticia de un departamento de policía. El repositorio contiene las soluciones personales de los ejercicios, no la aplicación ni la base de datos original.

## Ejercicios

| Ejercicio | Archivo |
|---:|---|
| 01 | [sql-police-department-1.sql](sql-police-department-1.sql) |
| 02 | [sql-police-department-2.sql](sql-police-department-2.sql) |
| 03 | [sql-police-department-3.sql](sql-police-department-3.sql) |
| 04 | [sql-police-department-4.sql](sql-police-department-4.sql) |
| 05 | [sql-police-department-5.sql](sql-police-department-5.sql) |
| 06 | [sql-police-department-6.sql](sql-police-department-6.sql) |
| 07 | [sql-police-department-7.sql](sql-police-department-7.sql) |
| 08 | [sql-police-department-8.sql](sql-police-department-8.sql) |
| 09 | [sql-police-department-9.sql](sql-police-department-9.sql) |
| 10 | [sql-police-department-10.sql](sql-police-department-10.sql) |

## Conceptos practicados

- `SELECT`, proyección de columnas y selección de registros.
- `WHERE`, condiciones y filtrado.
- `DISTINCT` para eliminar resultados duplicados.
- `ORDER BY` con ordenación ascendente y descendente.
- `LIMIT` para restringir el número de filas devueltas.

## Ejecución

Las consultas deben ejecutarse en el motor SQL y sobre el esquema de datos proporcionado por el ejercicio. El repositorio no incluye un volcado de la base de datos ni crea las tablas, por lo que las consultas no son autónomas.

## Autoría y atribución

Las consultas y notas son trabajo personal de práctica. El enunciado, la plataforma y el modelo de datos del ejercicio pertenecen a sus respectivos titulares.

## Project showcase

[Open the GitHub Pages showcase](https://tzayadet.github.io/SQL-Police-Department/) · [Showcase source](docs/index.html)

The page is an index of the SQL solutions; it does not run a database engine. To publish it, select **Settings → Pages → Build and deployment → Source → GitHub Actions** and set the repository Actions variable `ENABLE_PAGES=true` under **Settings → Secrets and variables → Actions → Variables**. The workflow remains skipped until that variable is enabled.
