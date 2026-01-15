# Piero Rojas Candio - Portafolio de proyectos

## 👋 Acerca de mí

Hola, soy **Piero Rojas**, Ingeniero de Sistemas de Información colegiado con más de **4 años de experiencia** en los sectores de **banca y consumo masivo**. A lo largo de mi trayectoria, he participado en procesos de auditoría, contabilidad, ventas y reclamos, generando propuestas de valor a través del **análisis de datos**, la **automatización y optimización de procesos**, y la **gestión de proyectos**.

Cuento con sólidos conocimientos en **Business Intelligence y Data Analytics**, trabajando con herramientas como **Power BI (DAX)**, **SQL Server / PL/SQL Oracle**, **Python**, **ETL** y **Excel**, las cuales he aplicado para transformar datos en información clara y accionable para la toma de decisiones. Estoy certificado como **PL-300: Microsoft Power BI Data Analyst Associate**, lo que respalda mi experiencia en modelado de datos, visualización y diseño de dashboards.

Durante mi experiencia profesional he desarrollado una fuerte orientación al negocio, colaborando estrechamente con equipos de TI y usuarios finales, asegurando la calidad de los datos, el rendimiento de las soluciones y una adecuada experiencia de usuario en los reportes.

En mi tiempo libre, disfruto seguir aprendiendo sobre nuevas herramientas y enfoques en analítica de datos, automatización y visualización, buscando constantemente mejorar mis habilidades técnicas y analíticas. Me caracterizo por mi **capacidad de análisis, comunicación efectiva, resolución de problemas y trabajo en equipo**.

📄 **Mi CV en PDF:** [CV - Piero Rojas Candio.pdf](https://github.com/pierorojascandio/Proyectos-Analisis-Datos/blob/main/CV%20-%20Piero%20Gilmar%20Rojas%20Candio.pdf)

Este repositorio tiene como objetivo **mostrar mis habilidades, compartir proyectos y documentar mi crecimiento profesional en el ámbito de Data Analytics y Business Intelligence**.

---

# Tabla de Contenidos

- [Acerca de mí](https://github.com/pierorojascandio/Data-Analysis-Portfolio/blob/main/README.md#acerca-de-mi)

Proyectos
- [Análisis de demanda y variación de precios con Python](https://github.com/pierorojascandio/Data-Analysis-Portfolio/blob/main/README.md#análisis-de-demanda-y-variación-de-precios-con-python)
- [Comparativa de Total Ingresos vs Año Anterior – ContosoSales](https://github.com/pierorojascandio/Data-Analysis-Portfolio/blob/main/README.md#comparativa-de-total-ingresos-vs-año-anterior--contososales)
- [Análisis histórico de ventas en la industria de videojuegos](https://github.com/pierorojascandio/Data-Analysis-Portfolio/blob/main/README.md#análisis-histórico-de-ventas-en-la-industria-de-videojuegos)

## 📝 Otras Secciones
- Herramientas y Tecnologías
- Contacto

---

# 📊 Análisis de demanda y variación de precios con Python

## Notebook
Puedes revisar el desarrollo completo del análisis en el siguiente notebook:

👉 [Proyecto de análisis de demanda y variación de precios.ipynb](https://github.com/pierorojascandio/Proyectos-Analisis-Datos/blob/main/Proyecto%20de%20an%C3%A1lisis%20de%20demanda%20y%20variaci%C3%B3n%20de%20precios.ipynb)

## Descripción
Proyecto de análisis de datos desarrollado en Python con el objetivo de **analizar la relación
entre la variación de precios y la demanda de productos**, y **proponer un enfoque predictivo
que apoye la toma de decisiones comerciales.**

El proyecto simula un caso de consultoría para una empresa comercializadora de productos,
enfocado en definir estrategias de precios competitivas basadas en datos.

## Objetivos
- Analizar el comportamiento de ventas frente a variaciones de precio.
- Identificar patrones entre precio base, precio final y unidades vendidas.
- Realizar análisis exploratorio y estadístico de los datos.
- Sentar las bases para un modelo predictivo de demanda.

## Fuente de datos
La fuente de datos es un archivo de texto que contiene información de ventas con las siguientes columnas:
- **ID:** Identificador de la venta
- **Store ID:** Identificador de la tienda
- **Total Price:** Precio final de venta
- **Base Price:** Precio base del producto
- **Units Sold:** Unidades vendidas

## Herramientas
- Python
- Pandas
- Numpy
- Scikit-learn
- Jupyter Notebook

## Proceso de Análisis
1. **Carga y exploración de datos**
   - Extracción y carga de información a un DataFrame
   - Identificación de tipos de datos, datos estadísticos y valores nulos

2. **Limpieza y preparación**
   - Corrección de registros inconsistentes
   - Creación y ajuste de variables relevantes

3. **Análisis exploratorio**
   - Comparación entre demanda, precio base y precio final
   - Análisis de unidades vendidas por tienda
   - Creación de un modelo predictivo en relación al precio final y demanda

4. **Insights**
   - Relación entre reducción de precios y aumento de demanda
   - Identificación de tiendas con mayor volumen de ventas

## Resultados
- Se identificó una relación directa entre variación de precios y unidades vendidas.
- El tratamiento adecuado de datos permitió mejorar la calidad del análisis.
- El proyecto demuestra el uso de Python como herramienta de análisis de datos aplicada a negocio.

---

# 📊 Comparativa de Total Ingresos vs Año Anterior – ContosoSales

## Demo del Dashboard
Puedes visualizar el funcionamiento del dashboard en el siguiente video:

👉 **[Ver demo del dashboard Power BI en Youtube](https://youtu.be/dPycNrLcFQA)**

## Descripción
Proyecto de Business Intelligence desarrollado en Power BI para la empresa
Contoso, enfocado en el análisis comparativo de los **ingresos totales del año actual
versus el año anterior**, permitiendo evaluar el desempeño financiero y la evolución de los
resultados en el tiempo.

El dashboard utiliza indicadores visuales tipo **semáforo**, facilitando la interpretación
rápida de los resultados por parte de usuarios de negocio.

## Objetivos
- Comparar el total de ingresos del año actual frente al año anterior.
- Identificar incrementos o disminuciones en los ingresos.
- Facilitar el análisis del desempeño financiero mediante indicadores claros.

## Fuente de datos
- Base de datos Microsoft Access (datos estructurados y normalizados para su consumo en Power BI)

## Herramientas
- Power BI Desktop (DAX)
- Power Query (ETL)
- Microsoft Access

## Proceso de Desarrollo

### 1. Extracción y Transformación de Datos (ETL)
- Conexión directa a la base de datos en Access.
- Limpieza y transformación de datos mediante Power Query.
- Validación de tipos de datos y consistencia de la información.
- Preparación del modelo para cálculos comparativos.

### 2. Modelado de Datos
- Definición de relaciones entre tablas.
- Preparación del modelo para análisis temporal.
- Optimización del modelo para el uso de medidas DAX.

### 3. Cálculo de Métricas con DAX
Se desarrollaron medidas DAX principalmente para:
- Total de ingresos del año actual.
- Total de ingresos del año anterior.
- Variación de ingresos interanual.
- Lógica condicional para indicadores visuales.

### 4. Visualización
- Diseño de un dashboard claro y ejecutivo.
- Implementación de **indicadores tipo semáforo**:
  - 🟢 **Verde**: ingresos mayores al año anterior.
  - 🔴 **Rojo**: ingresos menores al año anterior.
- Enfoque en lectura rápida y toma de decisiones.

## Resultados
- Visualización inmediata del desempeño financiero.
- Identificación rápida de periodos con crecimiento o caída de ingresos.
- Dashboard orientado a usuarios no técnicos y tomadores de decisión.

---

# 📊 Análisis histórico de ventas en la industria de videojuegos

## Demo del Dashboard
Puedes visualizar el funcionamiento del dashboard en el siguiente video:

👉 **[Ver demo del dashboard Power BI en Youtube](https://youtu.be/ZmgXrKBB3Sc)**

## Descripción
Proyecto de Business Intelligence orientado al análisis histórico de ventas en la industria
de videojuegos, utilizando Power BI como herramienta de visualización y Power Query
para el proceso de transformación y preparación de los datos.

El objetivo del dashboard es **permitir el análisis de las ventas a lo largo del tiempo,
identificando tendencias, mercados relevantes y desempeño por categorías clave dentro
de la industria.**

## Objetivos
- Analizar el comportamiento histórico de ventas en la industria de videojuegos.
- Identificar tendencias de crecimiento y periodos de mayor demanda.
- Comparar ventas por regiones, plataformas y categorías.

## Fuente de Datos
- Archivo Excel con información histórica de ventas de videojuegos (datos estructurados y tratados previamente para su análisis en Power BI)

## Herramientas
- Power BI Desktop
- Power Query (ETL)
- Microsoft Excel

## Proceso de Desarrollo

### 1. Carga y Transformación de Datos
- Importación del dataset desde Excel.
- Limpieza y estandarización de columnas.
- Conversión de tipos de datos.
- Eliminación de valores inconsistentes.
- Creación de columnas derivadas necesarias para el análisis.

> Todo el proceso ETL se realizó utilizando **Power Query**, asegurando un modelo limpio
y optimizado para visualización.

### 2. Modelado
- Estructuración del modelo de datos orientado al análisis histórico.
- Preparación del dataset para facilitar filtros y segmentaciones.

> No fue necesario el uso de DAX, ya que las métricas requeridas se obtuvieron
directamente desde el modelo transformado.

### 3. Visualización
- Diseño de un dashboard intuitivo y de fácil navegación.
- Uso de filtros para exploración por periodos y categorías.
- Gráficos claros orientados a análisis temporal y comparativo.

## Resultados
- Identificación de tendencias históricas en las ventas de videojuegos.
- Visualización clara de mercados y periodos con mayor volumen de ventas.
- Dashboard preparado para análisis exploratorio y toma de decisiones.
