# 📊 Tecno Max: Business Intelligence & Sales Analytics
**Proyecto de Análisis de Datos de Extremo a Extremo en Power BI**

Este repositorio contiene la solución integral de BI para **Tecno Max**, una empresa de retail tecnológico. El objetivo principal fue transformar datos transaccionales crudos en un tablero de control estratégico que permita optimizar la toma de decisiones comerciales, analizando el rendimiento de ventas, sucursales y fuerza de ventas.

---

## 🛠️ Stack Tecnológico
* **Power BI Desktop:** Modelado, DAX y Visualización.
* **Power Query (M):** Procesos de ETL (Extracción, Transformación y Carga).
* **Excel/CSV:** Fuentes de datos transaccionales.
* **Modelado Dimensional:** Implementación de Star Schema (Esquema en Estrella).

---

## 🏗️ Arquitectura de la Solución

### 1. Ingesta y Transformación (ETL)
Se realizó una limpieza profunda de datos utilizando **Power Query**, asegurando la integridad de la información mediante:
* Estandarización de tipos de datos y manejo de valores nulos.
* Creación de columnas personalizadas para segmentación.
* Normalización de las tablas de dimensiones.

### 2. Modelado de Datos (Star Schema)
El corazón del proyecto es un modelo robusto diseñado para el alto rendimiento:
* **Tabla de Hechos:** `Tickets` (Ventas, cantidades y montos).
* **Tablas de Dimensiones:** `Calendario`, `Clientes`, `Productos`, `Vendedores` y `Sucursales`.
* **Relaciones:** Configuración de cardinalidad 1:* con integridad referencial.



### 3. Lógica de Negocio (DAX)
Se desarrollaron medidas avanzadas para obtener insights críticos:
* **KPIs Base:** Ventas Totales, Ticket Promedio y Conteo de Productos.
* **Time Intelligence:** Comparativas de ventas contra el mes anterior y proyecciones anuales.
* **Análisis de Dispersión:** Correlación entre volumen de ventas y cantidad de vendedores.

---

## 📈 Visualización e Insights
El tablero final ofrece una experiencia de usuario interactiva (UX) dividida en:
* **Análisis Temporal:** Evolución de ventas 2021-2022.
* **Mapa de Calor:** Identificación de los días de mayor actividad comercial (Lunes a Sábado).
* **Rendimiento Geográfico:** Comparativa entre sucursales (Monterrey, Torreón, Monclova, etc.).



---

## 📁 Contenido del Repositorio
* `/Proyecto_TecnoMax_Vladimir.pbix`: Archivo ejecutable de Power BI.
* `/Data`: Carpeta con los archivos fuente (Excel/CSV) utilizados.
* `/Screenshots`: Capturas de pantalla del modelo y el tablero.

---

## 🚀 Cómo utilizar este proyecto
1. Descarga el archivo `.pbix` de este repositorio.
2. Abre el archivo con **Power BI Desktop**.
3. *Nota:* Si los datos no cargan inicialmente, dirígete a "Transformar Datos" > "Configuración de origen de datos" y actualiza la ruta hacia los archivos de la carpeta `/Data`.

---
**Desarrollado por Vladimir Angarita** *Software Developer & Data Enthusiast*
