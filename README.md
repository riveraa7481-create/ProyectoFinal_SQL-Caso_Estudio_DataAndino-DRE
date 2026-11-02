# Proyecto Final SQL – Análisis de cancelaciones de reservas hoteleras

## Descripción del proyecto

Este proyecto consiste en analizar los datos de reservas del hotel DataAndino utilizando SQL en Databricks. El objetivo fue conocer el comportamiento de las cancelaciones e identificar algunos factores relacionados con ellas, como las solicitudes especiales, los cambios en las reservas, la presencia de hijos y el precio promedio de las habitaciones.

Durante el desarrollo trabajé con consultas SQL para explorar los datos, realizar cálculos y relacionar diferentes tablas.

## Herramientas utilizadas

- **SQL:** consultas, filtros, agrupaciones, funciones de agregación y relaciones entre tablas.
- **Databricks:** entorno utilizado para trabajar y ejecutar las consultas SQL.
- **GitHub:** almacenamiento y documentación del proyecto.

## Fuente de datos

Los datos utilizados fueron obtenidos de Kaggle:

https://www.kaggle.com/datasets/datacertlaboratoria/sql-proyecto-1-analisis-de-cancelaciones-hoteleras

El conjunto de datos contiene información sobre reservas de hoteles, incluyendo fechas de llegada, tipo de hotel, cantidad de huéspedes, precios, solicitudes especiales y estado de cancelación.

## Desarrollo del proyecto

Durante el proyecto realicé diferentes actividades para trabajar y analizar la información:

- Exploración de las tablas y sus columnas.
- Creación y modificación de tablas para realizar los ejercicios.
- Generación de identificadores para las reservas.
- Creación de tablas adicionales para países, vendedores y facturas.
- Relación de tablas mediante diferentes tipos de `JOIN`.
- Clasificación de reservas utilizando `CASE WHEN`.
- Cálculo de tasas de cancelación con `AVG()`.
- Uso de funciones de agregación, ordenamiento y funciones de ventana.

También utilicé una tabla de prueba para realizar modificaciones sin alterar la información original.

## Principales resultados

A partir de las consultas realizadas, se identificaron los siguientes resultados:

- **Solicitudes especiales:** las reservas sin solicitudes especiales presentaron una tasa de cancelación del 48.31%, mientras que las reservas con cinco solicitudes registraron un 5%.

- **Cambios en las reservas:** las reservas que tuvieron entre 1 y 3 cambios presentaron una tasa de cancelación del 15.89%. En cambio, las reservas sin cambios alcanzaron el 41.24%.

- **Reservas con hijos:** las reservas con hijos presentaron una tasa de cancelación del 35.24%, frente al 37.67% de las reservas sin hijos.

- **Precio promedio:** el Resort Hotel registró un precio promedio de 106.59 en sus reservas canceladas, mientras que el City Hotel registró 105.10. Sin embargo, el City Hotel tuvo una mayor cantidad de cancelaciones.

Estos resultados permiten observar diferencias en el comportamiento de las reservas según sus características.

## Conclusión

Este proyecto me permitió reforzar mis conocimientos de SQL y aprender a trabajar con diferentes tablas y estructuras de datos en Databricks.

Además, pude practicar la limpieza y transformación de información, el uso de identificadores y las relaciones entre tablas mediante diferentes tipos de JOIN.

Fue una oportunidad para aplicar lo aprendido en un caso práctico y seguir desarrollando mis habilidades en el área de datos.
