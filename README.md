# 📊 Análisis de Ventas Globales – Dashboard en Power BI

Este repositorio contiene un proyecto de **análisis de datos y visualización en Power BI**, desarrollado como parte del **Máster en Data Science e IA Generativa en Evolve Academy**.

El objetivo del proyecto fue construir un **dashboard completo de Business Intelligence**, recorriendo todo el proceso desde la preparación de los datos hasta la creación de un informe interactivo para analizar el rendimiento del negocio.

---

# 📁 Dataset

Para el desarrollo del proyecto se utilizó el dataset **Global Superstore**, disponible en Kaggle.

Este dataset contiene información sobre ventas de una empresa de retail a nivel global entre **2011 y 2014**, incluyendo datos sobre:

- Pedidos  
- Clientes  
- Productos  
- Mercados  
- Envíos  
- Ventas y beneficios  

Este tipo de dataset es muy utilizado para practicar **análisis comercial y creación de dashboards de Business Intelligence**.

---

# 🔄 Proceso del proyecto

El desarrollo del informe siguió las etapas habituales de un proyecto de **Business Intelligence**.

## 1️⃣ Preparación y transformación de datos

Se realizó la limpieza y transformación de los datos utilizando **Power Query**.

Entre las principales transformaciones realizadas:

- Conversión de tipos de datos (fechas, números y divisas)  
- Eliminación de columnas innecesarias  
- Eliminación de duplicados  
- Creación de identificadores para el modelo  
- Separación del dataset en tablas de hechos y dimensiones  

---

## 2️⃣ Modelado de datos

Se construyó un **modelo en estrella (Star Schema)** para optimizar el análisis.

### Tabla de hechos

- `Fact_Sales`

### Tablas de dimensiones

- `Dim_Product`
- `Dim_Customer`
- `Dim_Geography`
- `Dim_Date`
- `Dim_Ship_Mode`
- `Dim_Priority`

Este modelo permite analizar las métricas del negocio de forma eficiente.

### Modelo de relaciones

_Aquí se puede incluir una captura del modelo de Power BI._

---

# 📈 Estructura del dashboard

El informe final está organizado en varias páginas que analizan diferentes aspectos del negocio.

## 📊 Visión general

Página principal con indicadores clave del negocio:

- Ventas totales  
- Crecimiento interanual  
- Beneficio  
- Indicadores de rendimiento  

---

## 🌍 Geografía y mercados

Análisis del rendimiento por región y país:

- Ventas por región  
- Distribución geográfica de ventas  
- Comparación entre mercados  

---

## 👥 Clientes y segmentos

Análisis del comportamiento de los clientes:

- Ventas por segmento  
- Top clientes  
- Ingreso medio por cliente  
- Rentabilidad por cliente  

---

## 📦 Productos y envíos

Análisis del catálogo y logística:

- Productos más vendidos  
- Ventas por categoría  
- Costes de envío  
- Tiempo de entrega por método de envío  

---

# ⚙️ Interactividad del informe

El dashboard incluye varios elementos interactivos que permiten explorar los datos.

## Filtros (Slicers)

Permiten segmentar el análisis por:

- Año  
- Región o mercado  
- Categoría de producto  
- Segmento de cliente  
- Método de envío  

---

## Marcadores (Bookmarks)

Se ha creado un **panel de filtros desplegable** que puede mostrarse u ocultarse mediante botones.

También se añadió un botón para **restablecer los filtros**.

---

## Drillthrough

El informe incluye páginas de **detalle de producto**, permitiendo profundizar en el rendimiento de un producto concreto.

---

## Tooltips personalizados

Se han creado tooltips personalizados para mostrar información adicional sobre clientes al pasar el cursor sobre ciertos elementos visuales.


---

# 🛠 Herramientas utilizadas

- Power BI  
- Power Query  
- Kaggle (dataset)
- Microsoft Fabric

---

# 📚 Aprendizajes del proyecto

Este proyecto permitió practicar y consolidar conceptos como:

- Modelado de datos en esquema estrella  
- Transformación de datos con Power Query  
- Diseño de KPIs  
- Desarrollo de dashboards interactivos  

---

# 👨‍💻 Autor

Proyecto desarrollado por **Óscar Fernández-Chinchilla López**

Máster en **Data Science e IA Generativa – Evolve Academy**
