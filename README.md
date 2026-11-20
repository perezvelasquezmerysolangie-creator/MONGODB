# TAREA 4 – ALMACENAMIENTO Y CONSULTAS DE DATOS EN BIG DATA

## Universidad Nacional Abierta y a Distancia – UNAD

**Curso:** Big Data  
**Actividad:** Tarea 4 – Almacenamiento y Consultas de Datos  
**Estudiante:** Mery Solangie Pérez Velásquez  
**Tutor:** Handry Orozco  
**Año:** 2026

---

## 1. Descripción del proyecto

Este proyecto desarrolla una implementación práctica de una base de datos NoSQL utilizando MongoDB Atlas.

Se busca aplicar técnicas de almacenamiento, administración, consulta y análisis de información mediante documentos BSON, colecciones y operaciones CRUD.

La implementación utiliza una colección denominada `usuarios`, con registros de prueba que permiten desarrollar consultas, filtros, actualizaciones, eliminaciones y operaciones de agregación.

## 2. Objetivo general

Analizar las bases de datos NoSQL y aplicar sus conceptos mediante el diseño, implementación y manipulación de datos con MongoDB, desarrollando consultas básicas, filtros, operadores y agregaciones en un contexto de Big Data.

## 3. Tecnologías utilizadas

- MongoDB Atlas: almacenamiento de datos en la nube.
- MongoDB Shell (mongosh): ejecución de comandos.
- Git y GitHub: control de versiones y publicación del proyecto.
- BSON / JSON: estructura de almacenamiento e intercambio de datos.

## 4. Conceptos principales

- NoSQL: bases de datos no relacionales.
- MongoDB: sistema de gestión de bases de datos documentales.
- Colecciones: agrupaciones de documentos.
- Documentos BSON: estructuras de información.
- CRUD: creación, lectura, actualización y eliminación.
- Aggregation Pipeline: procesamiento y análisis de datos.

## 5. Implementación

La actividad contempla:

1. Creación de la base de datos.
2. Creación de la colección de usuarios.
3. Inserción de al menos 100 documentos de prueba.
4. Consultas de selección y filtrado.
5. Actualización y eliminación de registros.
6. Consultas de agregación.
7. Análisis e interpretación de resultados.

## 6. Comandos principales

| Operación | Comando |
|---|---|
| Mostrar bases de datos | `show dbs` |
| Seleccionar base de datos | `use solangie` |
| Consultar colección | `db.usuarios.find()` |
| Insertar documento | `insertOne()` |
| Insertar varios | `insertMany()` |
| Actualizar | `updateOne()` |
| Actualizar varios | `updateMany()` |
| Eliminar | `deleteOne()` |
| Consultar estadísticas | `aggregate()` |

## 7. Resultados esperados

- Administración de documentos en MongoDB.
- Ejecución de consultas con filtros.
- Obtención de estadísticas mediante agregaciones.
- Comprensión de las ventajas de las bases de datos NoSQL.
- Aplicación de herramientas de almacenamiento y análisis de datos en escenarios Big Data.

## 8. Estructura del repositorio

- `documentos/`: informe de la actividad.
- `scripts/`: comandos y consultas MongoDB.
- `evidencias/`: capturas de implementación.
- `referencias/`: fuentes bibliográficas.

## 9. Autoría

Proyecto académico desarrollado como parte del curso Big Data de la Universidad Nacional Abierta y a Distancia – UNAD.

**Año 2026.**
