# 📊Análisis de la Base de Costos con Media Móvil Simple (SMA 200)

## 📌Descripción del proyecto

Este proyecto implementa una consulta SQL para el análisis de la base de costos de un activo financiero, utilizando la Media Móvil Simple de 200 períodos (SMA 200) como referencia de tendencia de largo plazo.

El objetivo es evaluar la posición relativa del precio y de la base de costos respecto a la SMA 200, permitiendo identificar escenarios de:
- Tendencia alcista o bajista
- Sobrevaluación o infravaluación
- Riesgo de ruptura de tendencia
- Señales de alerta para toma de decisiones financieras

## 🎯Objetivos del proyecto

- Calcular la SMA 200 mediante SQL.
- Analizar la evolución de la base de costos en el tiempo.
- Comparar precio, costo y tendencia de largo plazo.
- Detectar situaciones de riesgo o cambio de tendencia.
- Automatizar el análisis técnico directamente desde la base de datos.

## 🏦Contexto financiero

La SMA 200 es uno de los indicadores técnicos más utilizados en mercados financieros:
- Actúa como referencia de tendencia estructural.
- Es utilizada por traders, analistas y gestores de cartera.
- Cruces del precio o del costo respecto a la SMA 200 suelen anticipar:
- Cambios de tendencia
- Aumentos de volatilidad
- Ajustes de estrategia

📌 Integrar este análisis en SQL permite llevar el análisis técnico al nivel de datos operativos.

## 🧠Lógica del análisis

La consulta SQL:
- Ordena los precios de forma temporal.
- Calcula la Media Móvil Simple de 200 períodos.
- Calcula o integra la base de costos del activo.

Compara:
- Precio vs SMA 200
- Base de costos vs SMA 200
- Clasifica el estado del activo, por ejemplo:
- Tendencia alcista / bajista
- Zona de riesgo
- Zona favorable

📌 La lógica puede adaptarse a distintos activos y horizontes temporales.

## 📊Ejemplos de análisis

- Base de costos por encima de la SMA 200 → posible sobreexposición.
- Precio por debajo de la SMA 200 → tendencia bajista.
- Cruce del precio o del costo con la SMA 200 → alerta de cambio de régimen.
- Separación creciente entre costo y tendencia → aumento de riesgo.

## 🛠️Tecnologías utilizadas

SQL

Compatible con:
- PostgreSQL
- SQL Server
- BigQuery
- Oracle
- MySQL (con ajustes menores)

## 📁Estructura del proyecto

├── analisis_de_la_base_de_costos-SMA200.sql
└── README.md

## ▶️Cómo utilizar la consulta

Abrir el archivo analisis_de_la_base_de_costos-SMA200.sql.

Ajustar:
- Tabla de precios
- Columna temporal
- Base de costos
- Ventana de cálculo (200 períodos)
- Ejecutar la consulta en el motor SQL.

Utilizar el resultado para:
- Reportes financieros
- Dashboards
- Alertas de riesgo
- Seguimiento de cartera

## 🚀Posibles extensiones

- Incorporar otras medias móviles (SMA 50, EMA).
- Detectar cruces automáticos (Golden / Death Cross).
- Calcular indicadores adicionales (RSI, volatilidad).
- Integrar con alertas automáticas.
- Visualizar resultados en Power BI / Tableau.

## 👤Autora

Flavia Hepp
Proyecto de SQL aplicado a análisis financiero y control de riesgo.
