# Manipulación de Datos y Transaccionalidad

Este repositorio contiene la solución sobre la manipulación de datos y transaccionalidad utilizando consultas SQL en PostgreSQL.

## Descripción

El objetivo es aplicar los conceptos y herramientas aprendidas en la manipulación de datos a través de consultas agrupadas, con el siguiente conjunto de datos sobre inscritos.

### Estructura de la tabla

La tabla **INSCRITOS** contiene información sobre las inscripciones en diferentes fechas y fuentes:

```sql
CREATE TABLE IF NOT EXISTS INSCRITOS (
    cantidad INT,
    fecha DATE,
    fuente VARCHAR
);
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (44, '2021-01-01', 'Blog');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (56, '2021-01-01', 'Página');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (39, '2021-01-02', 'Blog');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (81, '2021-01-02', 'Página');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (12, '2021-01-03', 'Blog');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (91, '2021-01-03', 'Página');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (48, '2021-01-04', 'Blog');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (45, '2021-01-04', 'Página');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (55, '2021-01-05', 'Blog');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (33, '2021-01-05', 'Página');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (18, '2021-01-06', 'Blog');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (12, '2021-01-06', 'Página');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (34, '2021-01-07', 'Blog');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (24, '2021-01-07', 'Página');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (83, '2021-01-08', 'Blog');
INSERT INTO INSCRITOS(cantidad, fecha, fuente) VALUES (99, '2021-01-08', 'Página');
```
