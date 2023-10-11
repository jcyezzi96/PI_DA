# <h1 align=center> **PROYECTO INDIVIDUAL** </h1>
# <h1 align=center>**`Data Analytics`**</h1>
<p align="center">
<img src=""  height=300>
</p>

## <h2 align=center>**¡Bienvenido/a a mi proyecto individual de Data Analytics!**</h2>

### **Contexto**

Los accidentes aéreos son eventos inesperados e indeseados que involucran aeronaves y provocan daños físicos a personas o a las propias aeronaves. Un accidente aéreo puede involucrar cualquier tipo de aeronave, incluyendo aviones comerciales, aviones privados, helicópteros, planeadores y globos aerostáticos.
Estos accidentes pueden ser causados por diversos factores, como errores humanos, fallos de equipos, problemas meteorológicos, problemas de mantenimiento, fallas en la gestión del tráfico aéreo, problemas de diseño o problemas de fabricación. Además, pueden tener graves consecuencias tanto en términos de pérdidas humanas como económicas.
Dada la importancia de la seguridad en la aviación, la industria, las autoridades reguladoras y los investigadores trabajan incansablemente para prevenir futuros accidentes. El estudio de la causalidad de los accidentes y cómo prevenirlos es fundamental para evitar pérdidas humanas y daños materiales significativos.

### **Rol a desarrollar**

En este proyecto, he asumido el rol de trabajar para la **Organización de Aviación Civil Internacional (OACI)**, un organismo de la Organización de las Naciones Unidas. La OACI quiere investigar en profundidad los accidentes aéreos ocurridos desde el comienzo del siglo XX. El objetivo principal es realizar un análisis de datos relacionado con estos accidentes y crear un dashboard que complemente los análisis con visualizaciones.
La OACI me proporcionó un conjunto de datos sobre accidentes de aviones.

#### `ETL` (Extract Transform Load)

Para preparar los datos para nuestro análisis, llevé a cabo un proceso de Extract, Transform, Load (ETL) en el conjunto de datos original en formato .csv. Aquí están los pasos clave que realicé:

<ol>
    <li><strong>Extracción (Extract)</strong>: Inicialmente, extraje el conjunto de datos .csv en un dataframe de Pandas para poder trabajar de manera efectiva con él.</li>
    <li><strong>Transformación (Transform)</strong>: En esta etapa, realicé varias transformaciones en los datos para garantizar su calidad y utilidad en el análisis.</li>
    <ul>
        <li><strong>Estandarización de Nombres de Columnas</strong>: Normalicé los nombres de las columnas para asegurarme de que fueran consistentes y más fáciles de entender.</li>
        <li><strong>Gestión de Valores Nulos</strong>: Donde encontré campos que contenían únicamente símbolos o caracteres no válidos, los transformé en valores NaN para facilitar futuros análisis y visualizaciones.</li>
        <li><strong>Cambio de Formato</strong>: Ajusté el formato de algunas columnas, como fechas o valores numéricos, para que fueran coherentes y comparables.</li>
        <li><strong>Creación de Columnas Adicionales</strong>: Agregué columnas con datos adicionales que consideré importantes para el Análisis Exploratorio de Datos (EDA). Estos datos adicionales enriquecieron nuestro conjunto de datos.</li>
    </ul>
    <li><strong>Carga (Load)</strong>: Una vez finalizada la fase de transformación, volví a guardar el dataframe resultante en un archivo .csv. Esta versión mejorada del conjunto de datos está lista para ser utilizada en nuestro análisis y en la creación del dashboard interactivo.</li>
</ol>

#### `EDA` (Exploratory Data Analysis)

Mi primer paso fue realizar un análisis exploratorio de los datos en un notebook. Documenté cada uno de los pasos que seguí, y agregué conclusiones en cada gráfico que utilicé. También utilicé celdas Markdown para explicar mis observaciones y seleccioné gráficos adecuados según la naturaleza de las variables.

#### `Dashboard`

El siguiente paso fue crear un dashboard funcional y coherente con el storytelling. Me aseguré que el dashboard incluyera filtros para explorar los datos de manera interactiva. El diseño se centró en facilitar la interpretación de la información, y elegí gráficos apropiados según las variables a visualizar.

#### `KPIs`

Dentro del dashboard, grafiqué y medí el KPI propuesto, que consiste en evaluar la disminución de un 10% en la tasa de fatalidad de la tripulación en los últimos 10 años, en comparación con la década anterior. Se define la **tasa de fatalidad de la tripulación** como el número total de tripulantes fallecidos en los accidentes registrados en la década, dividido en la cantidad total de accidentes aéreos ocurridos en ese período de tiempo.
