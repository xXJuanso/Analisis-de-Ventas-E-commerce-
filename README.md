# Analisis-de-Ventas-E-commerce-
Análisis de ventas de una tienda de comercio electrónico de tecnología utilizando SQL, Google Sheets y Power BI.
# 📊Análisis de ventas de tecnología de comercio electrónico

Análisis de ventas de una tienda de comercio electrónico de tecnología utilizando una base de datos relacional creada desde cero en PostgreSQL, con resultados visualizados en Google Sheets.


---

## 🛠️ Herramientas Usadas

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)

---

## 🗄️Estructura de la base de datos

5 related tables built from scratch:

| Tabla | Descripcion | 
|---|---|
| `clientes` | Datos de los Clientes  | 
| `productos` | Catalogo de Productos | 
| `categorias` | Categoria de Productos | 
| `ordenes` | Ordenes | 
| `productos_ordenados` | Lines de pedidos| 

---

## 🔍Preguntas de negocios respondidas

### Query 1 — Master Sales Report
**"What is the full detail of every sale: customer, country, 
product, category, price and date?"**

Demonstrates JOIN across all 5 tables. Exported to Google Sheets 
as the master dataset.

---

### Query 2 — Revenue by Product Category
**"Which product category generates the most revenue?"**

Uses GROUP BY, SUM and AVG to calculate total revenue and 
average price per category.

---

### Query 3 — Monthly Sales Trend
**"How did sales evolve month by month throughout the year?"**

Uses EXTRACT and GROUP BY to calculate monthly revenue and 
order volume over time.

---

### Query 4 — Top 10 Customers by Total Spend
**"Who are our most valuable customers?"**

Ranks customers by total amount spent using ORDER BY and LIMIT.

---

### Query 5 — Cancellation Rate by Country
**"Which countries have the highest order cancellation rate?"**

Uses CASE WHEN to calculate cancellation rate per country, 
filtered with HAVING to ensure statistical relevance.

---

## 📁 Repository Structure
