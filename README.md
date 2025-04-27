# Análisis de Ecommerce
**Exploración de ventas, segmentación de clientes y recomendaciones estratégicas**  

[Dataset utilizado](https://github.com/JavierRamirez14/analisis_ecommerce/blob/main/data/) | [Informe completo en PDF](https://github.com/JavierRamirez14/analisis_ecommerce/blob/main/informe_analisis.pdf)

## Objetivo
Realizar un análisis integral de datos de ventas para:
- Identificar tendencias clave y rendimiento de productos  
- Segmentar clientes mediante modelo RFM  
- Proponer oportunidades para incrementar facturación  

## ¿Qué problemas resuelve?
- **Identificación de tendencias** estacionales y patrones de compra  
- **Evaluación de productos**: Best-sellers vs bajo rendimiento  
- **Segmentación avanzada** de clientes (RFM y análisis de cohortes)  
- **Recomendaciones accionables** basadas en datos  

## Estructura del Proyecto
## Variables Clave
| Variable            | Descripción                              |
|---------------------|------------------------------------------|
| Order ID          | ID único de compra                       |
| Product           | Nombre del producto                      |
| Quantity Ordered  | Unidades compradas                       |
| Price Each        | Precio unitario (USD)                    |
| Order Date        | Fecha/hora de compra                     |
| Purchase Address  | Dirección de envío                       |

## Metodología
### 1. Preprocesamiento
- Unificación de 12 datasets mensuales  
- Limpieza de datos y corrección de formatos  
- Creación de variables:
  - Temporales (mes, hora)  
  - Geográficas (ciudad, estado)  
  - RFM (Recency-Frequency-Monetary)  

### 2. Análisis por Áreas
#### Cliente
- Segmentación RFM  
- Cálculo de LTV (Lifetime Value)  
- Análisis de cohortes  

#### Producto
- Identificación de best-sellers  
- Relación precio-volumen  

#### Sesión
- Productos por sesión  
- Horarios de mayor actividad  

#### Localización
- Análisis geográfico de ventas  

### 3. Visualización
- Gráficos de tendencias  
- Mapas de calor geográficos  

## Insights Clave
![Segmentación RFM](https://github.com/JavierRamirez14/analisis_ecommerce/blob/main/rfm_analysis.png?raw=true)  

**Principales hallazgos**:  
- **Horario pico**: 60% de ventas entre 19:00-21:00  
- **Producto más vendido**: Cable USB (23% de ventas totales)  
- **Zona clave**: San Francisco (35% de ingresos)  

## Cómo Ejecutar
1. Clonar repositorio:
```bash
git clone https://github.com/JavierRamirez14/analisis_ecommerce.git
