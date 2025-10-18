# 🚗 FAST - Power BI Dashboard  

Este proyecto presenta el análisis de **FAST**, una empresa ficticia que ofrece servicios de transporte del tipo **Uber o Cabify**, desarrollado íntegramente en **Power BI**.  

El objetivo fue **analizar y visualizar el rendimiento operativo, financiero y de satisfacción del servicio**, aplicando técnicas de **Power Query, DAX, modelado de datos y diseño visual** para construir un dashboard profesional, moderno e intuitivo.  

---

## 🧭 Contexto del proyecto  

Este dashboard fue elaborado a partir de un **dataset ficticio** proporcionado durante mi **pasantía de datos en Artech**, y utiliza información simulada proveniente de la **India**.  

> 💡 Todos los valores monetarios se encuentran en formato rupia india.  
> 🗓️ Los datos corresponden al año **2024**  
> 🗣️ El dashboard y sus secciones están completamente en inglés.  

---

## 🧩 Objetivos del análisis  

- Comprender el **rendimiento general del negocio** (revenue, rides, ratings, cancelaciones).  
- Analizar los **métodos de pago**, las **razones de cancelación** y su evolución en el tiempo.  
- Evaluar la **eficiencia y desempeño de los vehículos** por tipo.  
- Ofrecer un diseño **visual, atractivo y fácil de interpretar** para cualquier usuario, técnico o no técnico.  

---

## 🚀 Habilidades y herramientas aplicadas  

### 🧮 Power Query   
- Estandarización y renombrado de columnas.  
- Creación de una **tabla calendario personalizada** (Calendar Table) con jerarquía anual, mensual y diaria.  

### ⚙️ DAX (Data Analysis Expressions)  
- Creación de **medidas personalizadas** para indicadores clave:  
  - `Total Rides`  
  - `Total Revenue`  
  - `Avg Revenue per Ride`  
  - `Avg Revenue per Customer`  
  - `Avg Driver Rating`  
  - `Avg Revenue per KM`  
  - `Cancelled Rides`  
  - `Cancellation Rate`  
- Uso de **COUNTROWS con DISTINCT**, **variables VAR**, y funciones como **CALCULATE**, **DIVIDE**, **KEEPFILTERS** y **IF/ISBLANK**.  
- Medidas dinámicas dependientes del contexto de filtros (por mes, tipo de ride, método de pago, etc.).  

### 📊 Visualización de datos  
- Construcción de dashboards con **navegación interna (paginado por botones)**.  
- Uso de **gráficos Donut, Line, Column, Matrix y Cards** para resaltar KPIs.  
- Segmentaciones dinámicas por mes, año y tipo de ride.  
- Diseño visual colorido, claro y moderno con coherencia entre páginas.   

### 🎨 Diseño en Figma  
- Creación del **logo y fondo principal (Home Page)**.  
- Definición del **color palette** y estilo visual consistente.  

---

## 🗂️ Estructura del dashboard  

El dashboard contiene **cinco secciones principales**, cada una diseñada con un propósito analítico específico y accesible mediante el menú de navegación interno:  

### 🏠 Home Page  
- Logo + fondo creados en **Figma**, 
- Botones de navegación a las distintas secciones.   
---

### 🌍 Overall  
> *Visión general del negocio.*  
- Filtro por mes del año 2024.  
- Donut Charts:  
  - **Revenue by Payment Method** (UPI, Cash, Uber Wallet, Credit Card, Debit Card).  
  - **Ride Status** (Completed, Cancelled by Driver, Cancelled by Customer, No Driver Found, Incomplete).  
- KPIs principales:  
  - Total Rides (Completed + Incomplete).  
  - Total Revenue.  
  - Avg Revenue per Ride.  
  - Avg Revenue per Customer.  
  - Avg Driver Rating.  
  - Avg Revenue per KM.  
  - Cancelled Rides.  
  - Cancellation Rate.  

---

### 💰 Revenue  
> *Análisis de ingresos y volumen de viajes en el tiempo.*  
- KPIs:  
  - Total Revenue.  
  - Avg Revenue per Ride.  
  - Avg Revenue per KM.  
- Visual: **Revenue and Ride Volume Over Time** (Line & Clustered Column Chart).  

---

### ❌ Cancellation  
> *Por qué y cuándo se cancelan los viajes.*  
- KPIs:  
  - Total Rides.  
  - Cancelled Rides.  
  - Cancellation Rate.  
- Gráficos:  
  - Cancelled Rides per Month (Line Chart).  
  - Reasons for Driver Cancellation (Donut Chart).  
  - Reasons for Customer Cancellation (Donut Chart).  

---

### 🚙 Vehicle  
> *Análisis de desempeño por tipo de vehículo.*  
- KPIs:  
  - Avg Revenue per Ride.  
  - Avg Driver Rating.  
  - Avg Revenue per KM.  
- Visuales:  
  - Quantity of Vehicles by Vehicle Type (Clustered Bar Chart).  
  - Matrix: Vehicle Type | Avg Ride Value | Avg Ride Distance | Avg Driver Rating.  

---

## 🧠 Insights y aprendizajes  
 
- Fortalecí el uso de **DAX avanzado** para construir KPIs precisos dependientes del contexto.  
- Profundicé en la **creación de dashboards interactivos y visualmente coherentes**.  
- Practiqué el uso de **Figma** para el diseño UI/UX dentro de Power BI.  
- Apliqué criterios de **data storytelling**, combinando claridad visual con profundidad analítica.  

---

## 🖼️ Capturas del Dashboard  

<table>
  <tr>
    <td align="center">
      <p>🏠 Home Page</p>
      <img width="400" src="./images/vistas/Fast Homepage.jpg" alt="Home Page"/>
    </td>
    <td align="center">
      <p>🌍 Overall Dashboard</p>
      <img width="400" src="./images/vistas/Fast Homepage.jpg" alt="Overall Dashboard"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <p>💰 Revenue Dashboard</p>
      <img width="400" src="./images/vistas/Fast Homepage.jpg" alt="Revenue Dashboard"/>
    </td>
    <td align="center">
      <p>❌ Cancellation Dashboard</p>
      <img width="400" src="./images/vistas/Fast Homepage.jpg" alt="Cancellation Dashboard"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <p>🚙 Vehicle Dashboard</p>
      <img width="400" src="./images/vistas/Fast Homepage.jpg" alt="Vehicle Dashboard"/>
    </td>
  </tr>
</table>

---

## 🛠️ Tecnologías utilizadas  

- **Power BI Desktop**  
- **Power Query**  
- **DAX (Data Analysis Expressions)**  
- **Figma** (para diseño visual y logotipo)  
- **CSV** (fuente de datos)  

---

## 📎 Créditos  

Proyecto realizado con datos ficticios como parte de mi **Pasantía en análisis de datos en Artech**.  
El dashboard fue diseñado, desarrollado y documentado íntegramente por **Maria Monchot**, con fines de aprendizaje y demostración de habilidades analíticas y de visualización en Power BI.  