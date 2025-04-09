# 🛒 Customer Journey y Análisis de Rentabilidad - Showz

Este proyecto tiene como objetivo analizar cómo las personas interactúan con la plataforma de comercio en línea **Showz**, desde su primer contacto hasta sus decisiones de compra, y evaluar la rentabilidad de las campañas de marketing mediante KPIs clave como el LTV y el ROMI.

## 📊 Objetivo

Investigar:

- Cómo usan los clientes el servicio (número de sesiones, frecuencia de retorno, duración).
- Cuándo empiezan a comprar y cuántas compras hacen.
- Cuánto dinero aporta cada cliente (Lifetime Value).
- En qué punto se recupera la inversión en adquisición de clientes (ROMI > 1).

## 📁 Datos utilizados

Se utilizaron tres datasets:

- `visits_log_us.csv`: visitas de usuarios desde enero de 2017 hasta diciembre de 2018.
- `orders_log_us.csv`: pedidos realizados, con fecha y monto.
- `costs_us.csv`: gastos de marketing por fuente y por día.

## 🔧 Procesamiento

- Conversión de columnas temporales a formato datetime.
- Cálculo de duración de sesiones.
- Agrupación por día, semana y mes.
- Cruce de fuentes de adquisición con ingresos para calcular KPIs.
- Limpieza de datos: valores nulos, tipos de datos, duplicados.

## 📈 Métricas clave analizadas

### Visitas
- Cantidad de usuarios únicos por día/semana/mes.
- Duración promedio de sesiones.
- Frecuencia de retorno de usuarios.

### Ventas
- Conversión por cohortes (días entre registro y primer pedido).
- Distribución de número de pedidos por cliente.
- Ingresos promedio por pedido.
- Lifetime Value (LTV) por cliente y por fuente de adquisición.

### Marketing
- Costo total por fuente de adquisición.
- Costo de adquisición por cliente (CAC).
- Rentabilidad (ROMI) por fuente de adquisición.

## 📉 Visualizaciones

Se incluyeron gráficos de líneas, histogramas y gráficos de barras para mostrar:

- Comportamiento de usuarios por día y hora.
- Ciclo de vida de clientes.
- Diferencias de comportamiento por fuente y dispositivo.
- Tendencias temporales en costos, ingresos y retorno.

## 💡 Conclusiones

- Se identificaron las fuentes de marketing con mejor relación costo-beneficio.
- Se detectaron cohortes con mejores tasas de conversión temprana.
- Se recomendó reasignar presupuesto a las fuentes con mayor ROMI.
- Se propusieron acciones para mejorar la retención y aumentar el LTV.

## 🛠 Herramientas utilizadas

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---

👨‍💻 Proyecto desarrollado como parte de mi portafolio de análisis de datos.  