# **PROYECTO INDIVIDUAL 2**

## **TEMA:** Siniestros viales

# <h1 align=center> **Federico Lopez** </h1>

### Desarrollo de la tematica:

Cuando hablamos de siniestros viales, hablamos de accidentes de tráfico o tránsito, en los que se involucran vehículos en las vías públicas, entre ellos automoviles, motos, bicicletas y tambien peatones.

Estos incidentes pueden desencadenar en consecuencias que van desde daños materiales hasta lesiones graves o fatales

Las tasas de mortalidad relacionadas con los siniestros viales suelen ser un inicador critico de la seguridad vial en una region. Reducir estas tasas es un iobjetivo clave para mejorar la seguridad vial y proteger la vida de las personas en la ciudad. En este caso, vamos a abarcar la ciudad de Buenos Aires. 

La prevencion de siniestros viales involucra medidas como la educacion vial, el cumplimiento de las normas de trafico, la infraestructura segura de carreteras y calles, asi como la promocion de vehiculos mas seguros. El seguimiento de las estadisticas y la implementacion de politicas efectivas son esenciales para abordar este problema de manera adecuada.


Fuente de informacion cacerca de datos de siniestros viales:

Sistema Nacional de Informacion Criminal(SNIC), del ministerio de Seguridad de la Nacion


##  **ROL A DESARROLLAR EN EL PROYECTO:**

El Observatorio de Movilidad y Seguridad Vial (OMVS), centro de estudios que se encuentra bajo la orbita de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, me solicita:
* La Elaboracion de un proyecto de análisis de datos, con el fin de generar informacion que le permita a las autoridades locales tomar medidas para disminuir la cantidad de victimas fatales de los siniestros viales.


#  **PROPUESTA DE TRABAJO**

### Tareas a realizar: 

* **EDA**: Documentar pasos con claridad, conclusiones correspondientes en cada gráfico empleado y analisis de lo que voy observando. Utilizar celdas Markdown para tal fin (la prolijidad se evaluará).
Suele ser que un EDA hata puede ser un entregable independiente.
Aspectos destacados necesarios: Busqueda de valores faltantes, valores atípicos/extremos u outliers y registros duplicados. Asimismo, la utilizacion de graficos coherentes segun tipología de variable que corresponda

* **Dashboard**: Debe ser funcional y coherente con el storytelling. Tiene que incluir filtros permitiendo asi explorar detalladamente los datos. Interactivo. El diseño tiene que ser facil la interpretacion de la informacion y su analisis. Claridad en la presentacion de los datos.

* **Analisis**: Ademas de la produccion de graficos con datos (dashboard), tambien se considerará los analisis y conclusiones que pueda extraer a partir de estos

* **KPIs**: Debo graficar y medir 2 KPIs:
    1- Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.

    Definimos a la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico. Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000


    2- Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

    Definimos a la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100

* **Repositorio de GitHUB**: El repo debe tener un ReadMe principal donde presenten, en una primera instancia, de forma general su proyecto y detallen qué hay en cada archivo/carpeta del propio repositorio. Este readme no puede ser el mismo que el entregado por Henry. El Readme debe incluir un REPORTE DE ANALISIS con base en los dashboards, asi como el analisis y la funcionalidad de los kpis sugeridos.


### **FUENTE DE DATOS**
* **OBLIGATORIA**:
    - [Buenos Aires Data](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales): El dataset denominado Homicidios 

# BREVE EXPLICACION:

* En este repo existe una carpeta llamada Data_inicial la cual contiene el archivo portador del dataset obligatorio para el proyecto llamado 'homicidios.xlsx'
* Un archivo llamado 'ETL_EDA_Hechos.ipynb' en donde hago un desarrollo de Exploratory Data Analisis, un breve procedimiento de ETL, donde termino combinando las tablas de mi archivo anteriormente mencionado. resultando de éste en un nuevo dataset el cual exporto en la carpeta de Data_inicial con el nombre de df_hechos_csv.csv el cual voy a utilizar para el dashboard realizado en PowerBI
* Este archivo README.md detallando un poco la informacion del repositorio
* El archivo Dashboard.pbix el cual contiene la presentacion de la informacion


