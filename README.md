# Analisis de Datos Alura Store Latam

Este proyecto realiza un estudio comparativo de rendimiento entre cuatro sucursales de la empresa Alura Store. El objetivo es identificar la unidad de negocio con menor desempeño financiero y operativo para recomendar su venta, permitiendo al propietario reinvertir el capital en un nuevo emprendimiento.

## Estructura del Proyecto

* data/: Directorio que contiene los archivos CSV (tienda_1 a tienda_4).
* AluraStoreLatam.ipynb: Notebook de Jupyter con el procesamiento de datos.
* requirements.txt: Dependencias del proyecto (Pandas, Matplotlib).

## Flujo de Trabajo en Git

El desarrollo se ejecuto bajo una arquitectura de ramas para garantizar un historial limpio y modular:

1. Rama main: Estado inicial del proyecyo.
2. Rama dev: Integracion final de todas las funcionalidades.
3. Ramas feature: Desarrollo independiente por actividad:
   * feature/analisis-ingresos
   * feature/ventas-categoria
   * feature/valoracion-media
   * feature/productos-extremos
   * feature/envio-promedio
   * feature/visualizacion-graficos

## Metricas Analizadas

### 1. Ingresos Totales
Calculo de la facturacion bruta de cada tienda. La Tienda 4 registro los ingresos mas bajos del grupo.

### 2. Volumen por Categoria
Conteo de ventas segmentado por tipo de producto para entender el nicho de cada sucursal.

### 3. Satisfaccion del Cliente
Promedio de calificaciones para medir la calidad del servicio post-venta.

### 4. Rotacion de Productos
Identificacion de los productos lideres en ventas y aquellos con nulo movimiento comercial.

### 5. Eficiencia Logistica
Analisis del costo de envio promedio para determinar el impacto de la logistica en el margen de beneficio.

## Visualizacion

Se implementaron tres tipos de graficos para el sustento del analisis:
* Grafico de barras: Comparativa de ingresos por sucursal.
* Grafico de dispersion: Relacion entre calificacion y costos de envio.
* Grafico circular: Composicion de categorias de la tienda con menor rendimiento.



## Conclusion y Recomendacion

Tras evaluar los indicadores, se recomienda la venta de la Tienda 4.

Justificacion:
Presenta los ingresos mas bajos de la red y una calificacion promedio que no compensa su baja facturacion. El costo de envio, aunque bajo, refleja una operacion de menor escala que no es prioritaria frente al potencial de crecimiento de las otras sucursales.

## Instalacion y Uso

1. Clonar el repositorio.
2. Instalar dependencias: pip install -r requirements.txt
3. Ejecutar AluraStoreLatam.ipynb en un entorno compatible con Jupyter.