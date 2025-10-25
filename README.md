# Dashboard de Productos Más Vendidos

## Descripción
Este proyecto crea una aplicación web interactiva para analizar ventas de productos en línea utilizando el conjunto de datos **"Online Retail"** del repositorio UCI.  
Permite explorar los productos más vendidos por país, visualizar gráficos interactivos de dispersión (Cantidad vs Precio Unitario) y realizar análisis estacional de las ventas diarias.

---

## Funcionalidades
- Menú desplegable para seleccionar un país
- Gráfico de barras con los 10 productos más vendidos por cantidad en el país seleccionado
- Callback que actualiza automáticamente el gráfico según la selección
- Análisis estacional de ventas diarias utilizando **Statsmodels**
- Gráfico de dispersión interactivo (Cantidad vs Precio Unitario) con **Altair**

---
## Datos

Se utiliza el conjunto de datos **"Online Retail"** disponible en el repositorio UCI:  
[https://archive.ics.uci.edu/ml/datasets/online+retail](https://archive.ics.uci.edu/ml/datasets/online+retail)

**Columnas importantes:**
- `InvoiceNo` : Número de factura
- `StockCode` : Código del producto
- `Description` : Nombre del producto
- `Quantity` : Cantidad vendida
- `UnitPrice` : Precio unitario
- `InvoiceDate` : Fecha de la factura
- `Country` : País del cliente

---

## Requisitos e Instalación

Para ejecutar este proyecto, se requiere Python 3 y las librerías listadas en el archivo `requirementsEV.txt`.

## Link a Google Colab
https://colab.research.google.com/drive/1Ile_HvmvWgl8kq1qgKR0nVhk0tmBNwhg?authuser=1#scrollTo=goYLfiBLlaBD

### Clonar el repositorio

```bash
git clone [https://github.com/Geo-27/Tareas-CD.git](https://github.com/Geo-27/ActividadEntornosVirtuales)
cd ActividadEntornosVirtuales

